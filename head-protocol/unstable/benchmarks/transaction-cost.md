--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-09 04:51:31.726893159 UTC |
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
| 1| 5840 | 10.38 | 3.29 | 0.51 |
| 2| 6041 | 12.46 | 3.94 | 0.55 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 169 | 747 | 42.62 | 12.24 | 0.62 |
| 4 | 228 | 858 | 51.12 | 14.69 | 0.71 |
| 5 | 283 | 969 | 64.05 | 18.14 | 0.84 |
| 6 | 339 | 1081 | 73.47 | 20.86 | 0.94 |
| 7 | 395 | 1196 | 86.31 | 24.29 | 1.08 |
| 8 | 450 | 1303 | 92.24 | 26.20 | 1.14 |
| 9 | 505 | 1414 | 92.01 | 26.61 | 1.15 |
| 10 | 562 | 1525 | 97.70 | 28.27 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1819 | 24.37 | 7.71 | 0.48 |
| 2| 1929 | 25.39 | 8.68 | 0.50 |
| 3| 2084 | 27.10 | 9.81 | 0.53 |
| 5| 2404 | 31.91 | 12.50 | 0.60 |
| 10| 3120 | 39.97 | 18.08 | 0.74 |
| 38| 7347 | 95.20 | 52.07 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 621 | 22.80 | 7.38 | 0.42 |
| 2| 773 | 24.25 | 8.44 | 0.44 |
| 3| 953 | 26.92 | 9.85 | 0.48 |
| 5| 1189 | 29.88 | 12.00 | 0.53 |
| 10| 2159 | 42.24 | 18.81 | 0.72 |
| 40| 6648 | 98.98 | 54.57 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.13 | 8.90 | 0.48 |
| 2| 824 | 31.54 | 10.26 | 0.52 |
| 3| 1006 | 31.61 | 10.96 | 0.53 |
| 5| 1335 | 35.71 | 13.45 | 0.59 |
| 10| 2082 | 45.24 | 19.47 | 0.75 |
| 36| 5812 | 94.96 | 50.71 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 700 | 33.83 | 10.16 | 0.53 |
| 2| 803 | 35.88 | 11.39 | 0.56 |
| 3| 979 | 38.66 | 12.84 | 0.60 |
| 5| 1263 | 42.61 | 15.27 | 0.66 |
| 10| 1897 | 52.82 | 21.42 | 0.81 |
| 29| 4993 | 99.77 | 47.24 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5788 | 27.13 | 9.11 | 0.69 |
| 2| 5916 | 34.76 | 11.63 | 0.78 |
| 3| 6116 | 44.72 | 15.02 | 0.89 |
| 4| 6307 | 54.53 | 18.40 | 1.00 |
| 5| 6435 | 63.83 | 21.46 | 1.10 |
| 6| 6791 | 76.27 | 25.83 | 1.25 |
| 7| 6651 | 77.56 | 25.99 | 1.26 |
| 8| 6931 | 94.07 | 31.74 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5868 | 22.55 | 7.67 | 0.65 |
| 10 | 5 | 285 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6174 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1138 | 6512 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1706 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 36 | 2049 | 7057 | 93.85 | 35.83 | 1.48 |

