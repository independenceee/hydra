--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-05 04:32:31.506970109 UTC |
| _Max. memory units_ | 14000000 |
| _Max. CPU units_ | 10000000000 |
| _Max. tx size (kB)_ | 16384 |

## Script summary

| Name   | Hash | Size (Bytes) 
| :----- | :--- | -----------: 
| νInitial | c8a101a5c8ac4816b0dceb59ce31fc2258e387de828f02961d2f2045 | 2652 | 
| νCommit | 61458bc2f297fff3cc5df6ac7ab57cefd87763b0b7bd722146a1035c | 685 | 
| νHead | a1442faf26d4ec409e2f62a685c1d4893f8d6bcbaf7bcb59d6fa1340 | 14599 | 
| μHead | fd173b993e12103cd734ca6710d364e17120a5eb37a224c64ab2b188* | 5284 | 
| νDeposit | ae01dade3a9c346d5c93ae3ce339412b90a0b8f83f94ec6baa24e30c | 1102 | 

* The minting policy hash is only usable for comparison. As the script is parameterized, the actual script is unique per head.

## `Init` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5837 | 10.61 | 3.37 | 0.52 |
| 2| 6039 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 14.59 | 4.61 | 0.58 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 29.28 | 9.24 | 0.79 |
| 43| 14282 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10040 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 171 | 747 | 41.61 | 12.04 | 0.61 |
| 4 | 226 | 858 | 50.96 | 14.65 | 0.71 |
| 5 | 281 | 969 | 64.11 | 18.19 | 0.84 |
| 6 | 340 | 1081 | 75.36 | 21.28 | 0.96 |
| 7 | 396 | 1192 | 86.53 | 24.35 | 1.08 |
| 8 | 449 | 1303 | 82.86 | 23.91 | 1.05 |
| 9 | 504 | 1414 | 98.52 | 28.06 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1979 | 26.58 | 9.01 | 0.52 |
| 3| 2116 | 28.13 | 10.10 | 0.54 |
| 5| 2383 | 31.05 | 12.25 | 0.59 |
| 10| 3209 | 41.94 | 18.62 | 0.76 |
| 41| 7800 | 98.33 | 54.95 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 660 | 22.50 | 7.30 | 0.41 |
| 2| 766 | 24.01 | 8.38 | 0.44 |
| 3| 973 | 26.06 | 9.59 | 0.47 |
| 5| 1092 | 27.11 | 11.23 | 0.50 |
| 10| 1969 | 38.65 | 17.78 | 0.68 |
| 42| 6687 | 98.92 | 55.91 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 664 | 29.09 | 8.89 | 0.48 |
| 2| 900 | 29.90 | 9.82 | 0.50 |
| 3| 907 | 32.69 | 11.22 | 0.54 |
| 5| 1214 | 37.02 | 13.78 | 0.60 |
| 10| 1982 | 46.92 | 19.87 | 0.76 |
| 35| 5686 | 93.63 | 49.67 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.79 | 10.15 | 0.53 |
| 2| 816 | 35.88 | 11.39 | 0.56 |
| 3| 892 | 37.24 | 12.41 | 0.58 |
| 5| 1275 | 42.65 | 15.28 | 0.66 |
| 10| 1900 | 52.52 | 21.35 | 0.81 |
| 29| 4916 | 98.93 | 47.00 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5838 | 27.05 | 9.08 | 0.69 |
| 2| 5916 | 34.83 | 11.65 | 0.78 |
| 3| 6104 | 44.83 | 15.10 | 0.89 |
| 4| 6185 | 51.36 | 17.26 | 0.96 |
| 5| 6329 | 60.41 | 20.29 | 1.06 |
| 6| 6494 | 69.44 | 23.35 | 1.17 |
| 7| 6421 | 73.34 | 24.47 | 1.20 |
| 8| 6999 | 94.81 | 32.01 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 568 | 6172 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1703 | 6849 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2221 | 7160 | 98.49 | 37.73 | 1.53 |

