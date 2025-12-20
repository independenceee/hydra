--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-20 04:36:36.539546367 UTC |
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
| 1| 5836 | 10.55 | 3.35 | 0.52 |
| 2| 6038 | 13.10 | 4.17 | 0.55 |
| 3| 6236 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 18.71 | 5.91 | 0.64 |
| 10| 7646 | 29.00 | 9.14 | 0.79 |
| 43| 14281 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 171 | 747 | 43.86 | 12.56 | 0.63 |
| 4 | 225 | 862 | 53.45 | 15.25 | 0.73 |
| 5 | 281 | 969 | 59.39 | 17.06 | 0.80 |
| 6 | 338 | 1081 | 70.82 | 20.34 | 0.92 |
| 7 | 394 | 1192 | 72.42 | 21.01 | 0.94 |
| 8 | 449 | 1303 | 99.64 | 28.03 | 1.21 |
| 9 | 505 | 1414 | 88.20 | 25.53 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 24.29 | 7.69 | 0.48 |
| 2| 1984 | 26.80 | 9.05 | 0.52 |
| 3| 2214 | 29.50 | 10.47 | 0.56 |
| 5| 2380 | 31.41 | 12.34 | 0.60 |
| 10| 3072 | 39.82 | 18.02 | 0.74 |
| 40| 7656 | 99.34 | 54.57 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.54 | 7.30 | 0.41 |
| 2| 784 | 25.59 | 8.80 | 0.46 |
| 3| 955 | 27.00 | 9.87 | 0.48 |
| 5| 1177 | 29.22 | 11.81 | 0.52 |
| 10| 2080 | 40.56 | 18.31 | 0.70 |
| 41| 6747 | 99.47 | 55.39 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 665 | 29.17 | 8.91 | 0.48 |
| 2| 736 | 30.27 | 9.86 | 0.50 |
| 3| 965 | 33.43 | 11.45 | 0.55 |
| 5| 1310 | 35.04 | 13.25 | 0.59 |
| 10| 1884 | 45.98 | 19.60 | 0.75 |
| 36| 6215 | 98.92 | 51.89 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.87 | 10.16 | 0.53 |
| 2| 852 | 36.60 | 11.61 | 0.57 |
| 3| 895 | 37.16 | 12.39 | 0.58 |
| 5| 1211 | 41.82 | 15.03 | 0.65 |
| 10| 2108 | 54.62 | 21.98 | 0.84 |
| 30| 4958 | 99.62 | 47.77 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.58 | 0.64 |
| 2| 6014 | 36.81 | 12.41 | 0.80 |
| 3| 6194 | 45.80 | 15.45 | 0.90 |
| 4| 6172 | 50.44 | 16.89 | 0.95 |
| 5| 6403 | 63.89 | 21.51 | 1.10 |
| 6| 6657 | 75.51 | 25.59 | 1.24 |
| 7| 6724 | 80.89 | 27.25 | 1.30 |
| 8| 6686 | 87.64 | 29.42 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1707 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2162 | 7124 | 96.88 | 37.08 | 1.51 |

