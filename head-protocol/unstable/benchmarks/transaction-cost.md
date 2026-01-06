--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-06 04:50:34.538568357 UTC |
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
| 1| 5837 | 10.28 | 3.25 | 0.51 |
| 2| 6037 | 12.84 | 4.08 | 0.55 |
| 3| 6239 | 14.59 | 4.61 | 0.58 |
| 5| 6641 | 18.71 | 5.91 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 170 | 747 | 41.22 | 11.92 | 0.60 |
| 4 | 228 | 862 | 49.27 | 14.22 | 0.69 |
| 5 | 283 | 969 | 56.10 | 16.24 | 0.76 |
| 6 | 339 | 1081 | 71.32 | 20.31 | 0.92 |
| 7 | 395 | 1196 | 72.65 | 21.07 | 0.94 |
| 8 | 449 | 1303 | 86.98 | 24.89 | 1.09 |
| 9 | 505 | 1414 | 88.61 | 25.63 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.00 | 7.62 | 0.48 |
| 2| 1940 | 25.55 | 8.71 | 0.50 |
| 3| 2130 | 27.97 | 10.06 | 0.54 |
| 5| 2439 | 32.44 | 12.63 | 0.61 |
| 10| 3150 | 40.63 | 18.26 | 0.75 |
| 40| 7641 | 97.58 | 54.08 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 599 | 22.57 | 7.30 | 0.41 |
| 2| 792 | 23.59 | 8.23 | 0.44 |
| 3| 940 | 27.10 | 9.89 | 0.48 |
| 5| 1280 | 30.12 | 12.06 | 0.54 |
| 10| 2094 | 41.75 | 18.66 | 0.71 |
| 43| 6751 | 99.61 | 56.69 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.54 | 8.47 | 0.46 |
| 2| 832 | 29.26 | 9.62 | 0.49 |
| 3| 940 | 30.90 | 10.74 | 0.52 |
| 5| 1258 | 34.90 | 13.21 | 0.58 |
| 10| 1963 | 47.14 | 19.95 | 0.76 |
| 34| 5851 | 95.36 | 49.63 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.15 | 9.95 | 0.52 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 891 | 37.24 | 12.41 | 0.58 |
| 5| 1406 | 44.44 | 15.82 | 0.69 |
| 10| 2005 | 54.09 | 21.82 | 0.83 |
| 28| 4675 | 95.84 | 45.43 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 27.13 | 9.10 | 0.69 |
| 2| 5956 | 35.96 | 12.08 | 0.79 |
| 3| 6041 | 43.95 | 14.72 | 0.88 |
| 4| 6316 | 55.64 | 18.79 | 1.01 |
| 5| 6448 | 64.01 | 21.53 | 1.11 |
| 6| 6742 | 76.45 | 25.84 | 1.25 |
| 7| 6575 | 76.28 | 25.60 | 1.24 |
| 8| 6760 | 88.07 | 29.58 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 568 | 6172 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2162 | 7124 | 96.88 | 37.08 | 1.51 |

