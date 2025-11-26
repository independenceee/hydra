--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-26 04:35:47.905107537 UTC |
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
| 1| 5837 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.53 | 3.97 | 0.55 |
| 3| 6238 | 14.59 | 4.61 | 0.58 |
| 5| 6640 | 18.88 | 5.97 | 0.64 |
| 10| 7647 | 29.31 | 9.25 | 0.79 |
| 43| 14279 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10048 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 170 | 747 | 41.51 | 12.02 | 0.61 |
| 4 | 227 | 858 | 53.94 | 15.36 | 0.73 |
| 5 | 281 | 974 | 59.29 | 17.03 | 0.79 |
| 6 | 338 | 1081 | 71.76 | 20.42 | 0.92 |
| 7 | 393 | 1192 | 87.03 | 24.51 | 1.08 |
| 8 | 453 | 1303 | 82.74 | 23.83 | 1.05 |
| 9 | 505 | 1414 | 89.15 | 25.82 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.37 | 7.71 | 0.48 |
| 2| 1882 | 24.43 | 8.40 | 0.49 |
| 3| 2106 | 28.42 | 10.17 | 0.55 |
| 5| 2462 | 33.15 | 12.84 | 0.62 |
| 10| 3159 | 41.83 | 18.59 | 0.76 |
| 38| 7338 | 96.14 | 52.35 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 654 | 22.77 | 7.37 | 0.42 |
| 2| 839 | 25.57 | 8.80 | 0.46 |
| 3| 926 | 26.90 | 9.84 | 0.48 |
| 5| 1286 | 31.10 | 12.35 | 0.55 |
| 10| 1956 | 38.65 | 17.79 | 0.68 |
| 42| 6742 | 98.53 | 55.80 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 27.51 | 8.47 | 0.46 |
| 2| 832 | 31.62 | 10.28 | 0.52 |
| 3| 1004 | 31.57 | 10.95 | 0.53 |
| 5| 1218 | 37.05 | 13.78 | 0.60 |
| 10| 1925 | 43.59 | 18.96 | 0.72 |
| 36| 6117 | 98.69 | 51.85 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.16 | 0.53 |
| 2| 833 | 35.85 | 11.38 | 0.56 |
| 3| 1008 | 38.51 | 12.80 | 0.60 |
| 5| 1251 | 42.61 | 15.27 | 0.66 |
| 10| 1873 | 51.96 | 21.17 | 0.81 |
| 28| 4847 | 98.11 | 46.10 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.05 | 9.07 | 0.69 |
| 2| 6035 | 36.68 | 12.38 | 0.80 |
| 3| 6086 | 44.99 | 15.14 | 0.89 |
| 4| 6242 | 54.89 | 18.48 | 1.00 |
| 5| 6425 | 65.35 | 22.01 | 1.12 |
| 6| 6562 | 74.43 | 25.08 | 1.22 |
| 7| 6880 | 84.40 | 28.49 | 1.34 |
| 8| 6943 | 94.73 | 31.97 | 1.45 |
| 9| 6876 | 96.90 | 32.58 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 568 | 6173 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1136 | 6511 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7159 | 98.93 | 37.88 | 1.54 |

