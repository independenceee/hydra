--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-09 04:39:08.911911233 UTC |
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
| 1| 5840 | 10.78 | 3.43 | 0.52 |
| 2| 6042 | 12.25 | 3.87 | 0.54 |
| 3| 6242 | 14.98 | 4.75 | 0.58 |
| 5| 6640 | 18.71 | 5.91 | 0.64 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10043 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 169 | 747 | 42.27 | 12.15 | 0.61 |
| 4 | 227 | 858 | 52.36 | 14.96 | 0.72 |
| 5 | 281 | 969 | 64.79 | 18.39 | 0.85 |
| 6 | 338 | 1081 | 70.73 | 20.13 | 0.91 |
| 7 | 395 | 1192 | 82.86 | 23.51 | 1.04 |
| 8 | 451 | 1303 | 88.06 | 25.25 | 1.10 |
| 10 | 560 | 1525 | 98.41 | 28.51 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1809 | 24.37 | 7.71 | 0.48 |
| 2| 1882 | 24.77 | 8.48 | 0.49 |
| 3| 2056 | 27.35 | 9.87 | 0.53 |
| 5| 2378 | 31.05 | 12.25 | 0.59 |
| 10| 3293 | 43.19 | 18.96 | 0.78 |
| 40| 7582 | 97.55 | 54.08 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.81 | 7.37 | 0.42 |
| 2| 858 | 25.06 | 8.68 | 0.45 |
| 3| 899 | 25.14 | 9.33 | 0.46 |
| 5| 1146 | 28.49 | 11.62 | 0.51 |
| 10| 1852 | 36.65 | 17.22 | 0.65 |
| 40| 6582 | 98.24 | 54.37 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 26.83 | 8.26 | 0.45 |
| 2| 897 | 29.90 | 9.82 | 0.50 |
| 3| 966 | 30.90 | 10.74 | 0.52 |
| 5| 1259 | 37.05 | 13.78 | 0.60 |
| 10| 2037 | 45.08 | 19.43 | 0.74 |
| 35| 5623 | 98.96 | 51.11 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 33.87 | 10.16 | 0.53 |
| 2| 893 | 36.64 | 11.62 | 0.57 |
| 3| 958 | 37.91 | 12.62 | 0.59 |
| 5| 1369 | 43.92 | 15.67 | 0.68 |
| 10| 2127 | 55.40 | 22.22 | 0.85 |
| 28| 4713 | 96.01 | 45.45 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 26.97 | 9.06 | 0.69 |
| 2| 5980 | 37.09 | 12.50 | 0.80 |
| 3| 6000 | 41.45 | 13.86 | 0.85 |
| 4| 6290 | 54.91 | 18.49 | 1.00 |
| 5| 6416 | 61.31 | 20.68 | 1.08 |
| 6| 6569 | 74.42 | 25.00 | 1.22 |
| 7| 6802 | 84.94 | 28.65 | 1.34 |
| 8| 7009 | 95.71 | 32.37 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6005 | 30.67 | 10.88 | 0.74 |
| 10 | 20 | 1139 | 6513 | 60.17 | 22.59 | 1.09 |
| 10 | 40 | 2275 | 7191 | 99.66 | 38.24 | 1.55 |

