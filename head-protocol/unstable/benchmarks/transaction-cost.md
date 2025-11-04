--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-04 04:22:22.010708748 UTC |
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
| 1| 5838 | 10.55 | 3.35 | 0.52 |
| 2| 6037 | 12.73 | 4.04 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.88 | 5.97 | 0.64 |
| 10| 7650 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 915 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 171 | 747 | 43.91 | 12.57 | 0.63 |
| 4 | 228 | 858 | 50.80 | 14.61 | 0.70 |
| 5 | 284 | 969 | 60.67 | 17.33 | 0.81 |
| 6 | 338 | 1081 | 69.82 | 19.95 | 0.91 |
| 7 | 394 | 1192 | 72.52 | 20.99 | 0.94 |
| 8 | 451 | 1303 | 93.31 | 26.41 | 1.15 |
| 9 | 504 | 1414 | 98.84 | 28.19 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1810 | 23.92 | 7.60 | 0.48 |
| 2| 1882 | 24.77 | 8.48 | 0.49 |
| 3| 2085 | 27.10 | 9.81 | 0.53 |
| 5| 2443 | 32.56 | 12.66 | 0.61 |
| 10| 2978 | 37.33 | 17.34 | 0.71 |
| 41| 7598 | 97.69 | 54.75 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 655 | 22.50 | 7.30 | 0.41 |
| 2| 765 | 23.65 | 8.24 | 0.43 |
| 3| 970 | 27.00 | 9.87 | 0.48 |
| 5| 1303 | 31.04 | 12.32 | 0.55 |
| 10| 1978 | 41.22 | 18.50 | 0.70 |
| 43| 6781 | 98.69 | 56.48 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 653 | 29.13 | 8.90 | 0.48 |
| 2| 843 | 31.62 | 10.27 | 0.52 |
| 3| 899 | 30.23 | 10.54 | 0.51 |
| 5| 1210 | 37.02 | 13.78 | 0.60 |
| 10| 1902 | 46.01 | 19.61 | 0.75 |
| 37| 6112 | 98.81 | 52.50 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.16 | 0.53 |
| 2| 807 | 35.89 | 11.39 | 0.56 |
| 3| 989 | 38.62 | 12.83 | 0.60 |
| 5| 1225 | 41.90 | 15.05 | 0.65 |
| 10| 2154 | 55.71 | 22.30 | 0.86 |
| 30| 4962 | 99.82 | 47.84 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5815 | 27.05 | 9.07 | 0.69 |
| 2| 5927 | 35.97 | 12.08 | 0.79 |
| 3| 6042 | 41.56 | 13.92 | 0.85 |
| 4| 6188 | 50.08 | 16.82 | 0.95 |
| 5| 6379 | 60.18 | 20.23 | 1.06 |
| 6| 6542 | 73.40 | 24.68 | 1.21 |
| 7| 6803 | 84.37 | 28.44 | 1.34 |
| 8| 6750 | 82.12 | 27.51 | 1.31 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 569 | 6173 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1137 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1708 | 6854 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2220 | 7159 | 98.49 | 37.73 | 1.53 |

