--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-21 04:32:11.172416706 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6638 | 18.84 | 5.95 | 0.64 |
| 10| 7651 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10076 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 42.23 | 12.15 | 0.61 |
| 4 | 227 | 858 | 48.05 | 13.95 | 0.68 |
| 5 | 283 | 969 | 63.70 | 18.09 | 0.84 |
| 6 | 340 | 1081 | 71.76 | 20.45 | 0.93 |
| 7 | 396 | 1192 | 75.30 | 21.83 | 0.97 |
| 8 | 451 | 1303 | 87.14 | 24.89 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.40 | 8.39 | 0.49 |
| 3| 2061 | 26.99 | 9.78 | 0.53 |
| 5| 2317 | 29.93 | 11.94 | 0.58 |
| 10| 3079 | 39.78 | 18.02 | 0.74 |
| 41| 7640 | 98.47 | 55.00 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 22.54 | 7.31 | 0.41 |
| 2| 828 | 25.10 | 8.68 | 0.45 |
| 3| 831 | 24.06 | 9.03 | 0.45 |
| 5| 1176 | 29.14 | 11.79 | 0.52 |
| 10| 1991 | 40.35 | 18.29 | 0.70 |
| 42| 6703 | 99.49 | 56.05 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.46 | 8.69 | 0.47 |
| 2| 774 | 30.98 | 10.08 | 0.51 |
| 3| 974 | 30.87 | 10.74 | 0.52 |
| 5| 1245 | 36.98 | 13.77 | 0.60 |
| 10| 1910 | 43.44 | 18.93 | 0.72 |
| 36| 5859 | 96.88 | 51.27 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 857 | 36.60 | 11.61 | 0.57 |
| 3| 997 | 38.55 | 12.81 | 0.60 |
| 5| 1340 | 43.24 | 15.47 | 0.67 |
| 10| 2084 | 54.77 | 22.02 | 0.84 |
| 28| 4721 | 95.59 | 45.37 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5818 | 27.13 | 9.11 | 0.69 |
| 2| 6008 | 36.93 | 12.44 | 0.80 |
| 3| 6075 | 44.97 | 15.10 | 0.89 |
| 4| 6266 | 53.71 | 18.06 | 0.99 |
| 5| 6356 | 62.85 | 21.11 | 1.09 |
| 6| 6497 | 69.41 | 23.36 | 1.17 |
| 7| 6602 | 79.76 | 26.85 | 1.28 |
| 8| 6803 | 84.48 | 28.42 | 1.34 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 22.55 | 7.67 | 0.65 |
| 10 | 10 | 571 | 6176 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1706 | 6852 | 81.11 | 30.83 | 1.33 |
| 10 | 39 | 2223 | 7163 | 97.61 | 37.43 | 1.52 |

