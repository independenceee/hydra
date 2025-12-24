--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-24 04:46:43.378596988 UTC |
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
| 1| 5837 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.72 | 4.03 | 0.55 |
| 3| 6236 | 14.67 | 4.64 | 0.58 |
| 5| 6641 | 18.81 | 5.94 | 0.64 |
| 10| 7650 | 29.40 | 9.28 | 0.79 |
| 43| 14279 | 99.23 | 31.02 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 171 | 747 | 44.01 | 12.62 | 0.63 |
| 4 | 227 | 858 | 53.71 | 15.31 | 0.73 |
| 5 | 282 | 969 | 64.05 | 18.18 | 0.84 |
| 6 | 338 | 1081 | 73.58 | 20.85 | 0.94 |
| 7 | 393 | 1192 | 86.34 | 24.26 | 1.08 |
| 8 | 448 | 1303 | 87.69 | 25.07 | 1.10 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1801 | 24.00 | 7.62 | 0.48 |
| 2| 1946 | 25.84 | 8.78 | 0.51 |
| 3| 2113 | 27.86 | 10.03 | 0.54 |
| 5| 2371 | 31.17 | 12.28 | 0.59 |
| 10| 3180 | 41.79 | 18.58 | 0.76 |
| 42| 7759 | 98.44 | 55.67 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.80 | 7.37 | 0.41 |
| 2| 723 | 22.60 | 7.95 | 0.42 |
| 3| 830 | 24.02 | 9.02 | 0.45 |
| 5| 1281 | 31.17 | 12.38 | 0.55 |
| 10| 2027 | 41.02 | 18.46 | 0.70 |
| 42| 6812 | 99.94 | 56.20 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 27.47 | 8.46 | 0.46 |
| 2| 736 | 30.19 | 9.84 | 0.50 |
| 3| 1010 | 31.69 | 10.98 | 0.53 |
| 5| 1222 | 36.95 | 13.76 | 0.60 |
| 10| 1935 | 46.80 | 19.84 | 0.76 |
| 36| 6006 | 97.90 | 51.62 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.79 | 10.15 | 0.53 |
| 2| 857 | 36.48 | 11.58 | 0.57 |
| 3| 975 | 38.51 | 12.80 | 0.60 |
| 5| 1344 | 43.31 | 15.48 | 0.67 |
| 10| 2027 | 54.89 | 22.05 | 0.84 |
| 29| 4773 | 96.64 | 46.29 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.08 | 9.09 | 0.69 |
| 2| 5922 | 36.04 | 12.11 | 0.79 |
| 3| 6173 | 45.68 | 15.43 | 0.90 |
| 4| 6148 | 50.52 | 16.91 | 0.95 |
| 5| 6426 | 61.22 | 20.64 | 1.08 |
| 6| 6343 | 67.40 | 22.58 | 1.14 |
| 7| 6778 | 80.37 | 27.04 | 1.29 |
| 8| 6761 | 88.07 | 29.57 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 5 | 286 | 6005 | 29.79 | 10.58 | 0.73 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2166 | 7128 | 96.44 | 36.92 | 1.51 |

