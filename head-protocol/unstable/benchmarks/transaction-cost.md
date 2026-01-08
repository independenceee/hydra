--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-08 04:50:19.642147108 UTC |
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
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7644 | 29.23 | 9.22 | 0.79 |
| 43| 14281 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 744 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 170 | 747 | 41.08 | 11.87 | 0.60 |
| 4 | 226 | 858 | 48.05 | 13.93 | 0.68 |
| 5 | 283 | 969 | 57.85 | 16.66 | 0.78 |
| 6 | 338 | 1081 | 69.85 | 19.96 | 0.91 |
| 7 | 396 | 1192 | 77.04 | 22.12 | 0.98 |
| 8 | 448 | 1303 | 91.62 | 25.96 | 1.13 |
| 9 | 507 | 1418 | 89.73 | 25.83 | 1.12 |
| 10 | 561 | 1525 | 99.57 | 28.71 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 22.92 | 7.32 | 0.47 |
| 2| 1980 | 26.96 | 9.09 | 0.52 |
| 3| 2085 | 27.24 | 9.84 | 0.53 |
| 5| 2315 | 29.89 | 11.93 | 0.58 |
| 10| 3168 | 40.67 | 18.27 | 0.75 |
| 39| 7281 | 92.18 | 51.93 | 1.59 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 662 | 22.77 | 7.37 | 0.42 |
| 2| 808 | 25.55 | 8.81 | 0.46 |
| 3| 853 | 24.07 | 9.03 | 0.45 |
| 5| 1152 | 28.15 | 11.51 | 0.51 |
| 10| 2149 | 42.78 | 18.98 | 0.73 |
| 42| 6589 | 98.17 | 55.66 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 27.51 | 8.47 | 0.46 |
| 2| 736 | 30.27 | 9.86 | 0.50 |
| 3| 1055 | 32.40 | 11.20 | 0.54 |
| 5| 1260 | 37.05 | 13.78 | 0.60 |
| 10| 2057 | 45.26 | 19.49 | 0.75 |
| 34| 5597 | 97.80 | 50.14 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 33.83 | 10.16 | 0.53 |
| 2| 900 | 36.56 | 11.60 | 0.57 |
| 3| 1004 | 38.51 | 12.80 | 0.60 |
| 5| 1331 | 43.21 | 15.46 | 0.67 |
| 10| 1986 | 53.71 | 21.72 | 0.83 |
| 30| 5017 | 99.73 | 47.88 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5787 | 27.13 | 9.09 | 0.69 |
| 2| 5939 | 35.89 | 12.05 | 0.79 |
| 3| 6083 | 44.92 | 15.07 | 0.89 |
| 4| 6190 | 52.72 | 17.66 | 0.98 |
| 5| 6416 | 63.71 | 21.43 | 1.10 |
| 6| 6732 | 75.49 | 25.45 | 1.24 |
| 7| 6792 | 84.31 | 28.45 | 1.34 |
| 8| 6947 | 94.28 | 31.85 | 1.45 |
| 9| 6930 | 94.99 | 31.92 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.96 | 7.01 | 0.63 |
| 10 | 5 | 284 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1137 | 6511 | 59.28 | 22.29 | 1.08 |
| 10 | 30 | 1707 | 6853 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2218 | 7158 | 97.16 | 37.28 | 1.52 |

