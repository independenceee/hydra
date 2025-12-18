--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-18 04:44:32.866221275 UTC |
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
| 1| 5834 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2181 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 33.33 | 9.66 | 0.52 |
| 3 | 171 | 747 | 39.82 | 11.57 | 0.59 |
| 4 | 226 | 858 | 48.05 | 13.98 | 0.68 |
| 5 | 282 | 969 | 55.96 | 16.24 | 0.76 |
| 6 | 337 | 1081 | 73.79 | 20.94 | 0.94 |
| 7 | 394 | 1192 | 82.41 | 23.36 | 1.04 |
| 8 | 448 | 1303 | 85.33 | 24.55 | 1.07 |
| 9 | 506 | 1418 | 98.25 | 28.00 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1799 | 24.37 | 7.71 | 0.48 |
| 2| 1942 | 25.43 | 8.68 | 0.50 |
| 3| 2109 | 28.31 | 10.14 | 0.54 |
| 5| 2359 | 31.49 | 12.36 | 0.60 |
| 10| 3139 | 40.82 | 18.31 | 0.75 |
| 41| 7806 | 99.00 | 55.19 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 610 | 22.57 | 7.32 | 0.41 |
| 2| 758 | 24.35 | 8.47 | 0.44 |
| 3| 954 | 26.13 | 9.61 | 0.47 |
| 5| 1302 | 31.33 | 12.40 | 0.55 |
| 10| 1790 | 36.00 | 17.05 | 0.64 |
| 40| 6551 | 97.22 | 54.06 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 27.54 | 8.47 | 0.46 |
| 2| 807 | 30.94 | 10.07 | 0.51 |
| 3| 1001 | 31.57 | 10.95 | 0.53 |
| 5| 1282 | 37.74 | 14.00 | 0.61 |
| 10| 2125 | 45.98 | 19.69 | 0.76 |
| 35| 5794 | 95.33 | 50.22 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 668 | 33.87 | 10.16 | 0.53 |
| 2| 764 | 35.17 | 11.17 | 0.55 |
| 3| 992 | 38.63 | 12.83 | 0.60 |
| 5| 1280 | 43.31 | 15.48 | 0.67 |
| 10| 1897 | 52.60 | 21.37 | 0.81 |
| 29| 4856 | 97.57 | 46.58 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5790 | 27.04 | 9.09 | 0.69 |
| 2| 5972 | 37.00 | 12.47 | 0.80 |
| 3| 6135 | 45.96 | 15.47 | 0.90 |
| 4| 6279 | 55.07 | 18.56 | 1.01 |
| 5| 6354 | 61.70 | 20.74 | 1.08 |
| 6| 6676 | 74.33 | 25.07 | 1.23 |
| 7| 6771 | 81.30 | 27.45 | 1.30 |
| 8| 6932 | 94.94 | 32.12 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 10 | 568 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1139 | 6514 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1707 | 6853 | 78.27 | 29.85 | 1.30 |
| 10 | 39 | 2218 | 7157 | 97.61 | 37.43 | 1.52 |

