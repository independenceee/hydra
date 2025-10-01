--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-01 04:15:10.593234382 UTC |
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
| 1| 5834 | 10.35 | 3.28 | 0.51 |
| 2| 6038 | 12.63 | 4.00 | 0.55 |
| 3| 6239 | 14.98 | 4.75 | 0.58 |
| 5| 6638 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10086 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 169 | 747 | 43.55 | 12.48 | 0.62 |
| 4 | 225 | 858 | 49.56 | 14.34 | 0.69 |
| 5 | 281 | 969 | 59.86 | 17.18 | 0.80 |
| 6 | 340 | 1081 | 64.06 | 18.57 | 0.85 |
| 7 | 394 | 1192 | 84.32 | 23.90 | 1.06 |
| 8 | 449 | 1303 | 80.78 | 23.41 | 1.03 |
| 9 | 504 | 1414 | 91.30 | 26.39 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1941 | 25.39 | 8.68 | 0.50 |
| 3| 2057 | 27.06 | 9.80 | 0.53 |
| 5| 2447 | 32.11 | 12.55 | 0.61 |
| 10| 3191 | 41.99 | 18.63 | 0.76 |
| 40| 7592 | 98.49 | 54.34 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 646 | 22.81 | 7.37 | 0.42 |
| 2| 776 | 24.32 | 8.46 | 0.44 |
| 3| 973 | 26.59 | 9.78 | 0.48 |
| 5| 1301 | 31.60 | 12.49 | 0.55 |
| 10| 2006 | 39.17 | 17.95 | 0.68 |
| 40| 6466 | 95.54 | 53.61 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.17 | 8.91 | 0.48 |
| 2| 824 | 31.62 | 10.28 | 0.52 |
| 3| 983 | 33.47 | 11.46 | 0.55 |
| 5| 1176 | 36.38 | 13.58 | 0.59 |
| 10| 1960 | 43.59 | 18.96 | 0.73 |
| 38| 6087 | 98.26 | 52.99 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 33.87 | 10.16 | 0.53 |
| 2| 807 | 35.81 | 11.37 | 0.56 |
| 3| 953 | 37.91 | 12.62 | 0.59 |
| 5| 1204 | 41.97 | 15.07 | 0.65 |
| 10| 2096 | 54.55 | 21.97 | 0.84 |
| 29| 4954 | 99.44 | 47.12 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5779 | 27.09 | 9.08 | 0.69 |
| 2| 5963 | 35.93 | 12.05 | 0.79 |
| 3| 6188 | 45.89 | 15.47 | 0.90 |
| 4| 6248 | 55.00 | 18.56 | 1.00 |
| 5| 6541 | 66.37 | 22.39 | 1.14 |
| 6| 6530 | 73.48 | 24.69 | 1.21 |
| 7| 6620 | 81.86 | 27.49 | 1.30 |
| 8| 6935 | 94.91 | 32.07 | 1.45 |
| 9| 6991 | 99.79 | 33.60 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 56 | 5867 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.65 | 10.19 | 0.72 |
| 10 | 20 | 1138 | 6513 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1706 | 6853 | 81.11 | 30.83 | 1.33 |
| 10 | 39 | 2221 | 7160 | 98.49 | 37.73 | 1.53 |

