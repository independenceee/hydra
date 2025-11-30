--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-30 04:44:18.09398975 UTC |
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
| 1| 5841 | 10.55 | 3.35 | 0.52 |
| 2| 6038 | 12.72 | 4.03 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 19.10 | 6.05 | 0.64 |
| 10| 7648 | 29.19 | 9.21 | 0.79 |
| 43| 14283 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.34 | 9.42 | 0.51 |
| 3 | 171 | 747 | 41.46 | 12.00 | 0.60 |
| 4 | 226 | 858 | 50.74 | 14.57 | 0.70 |
| 5 | 282 | 969 | 57.67 | 16.65 | 0.78 |
| 6 | 342 | 1081 | 72.90 | 20.72 | 0.94 |
| 7 | 395 | 1192 | 84.34 | 23.82 | 1.06 |
| 8 | 451 | 1307 | 98.20 | 27.49 | 1.20 |
| 9 | 506 | 1418 | 94.46 | 27.10 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1807 | 24.00 | 7.62 | 0.48 |
| 2| 1928 | 25.84 | 8.78 | 0.51 |
| 3| 2106 | 28.13 | 10.10 | 0.54 |
| 5| 2280 | 28.86 | 11.64 | 0.57 |
| 10| 3161 | 40.55 | 18.24 | 0.75 |
| 41| 7707 | 99.44 | 55.24 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 646 | 22.54 | 7.31 | 0.41 |
| 2| 840 | 25.17 | 8.70 | 0.45 |
| 3| 917 | 27.06 | 9.88 | 0.48 |
| 5| 1349 | 31.15 | 12.35 | 0.55 |
| 10| 1953 | 39.45 | 18.01 | 0.68 |
| 39| 6268 | 93.51 | 52.35 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 606 | 28.46 | 8.69 | 0.47 |
| 2| 766 | 28.47 | 9.38 | 0.48 |
| 3| 944 | 30.86 | 10.73 | 0.52 |
| 5| 1261 | 34.89 | 13.21 | 0.58 |
| 10| 1918 | 46.70 | 19.82 | 0.75 |
| 35| 5584 | 97.19 | 50.59 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 33.87 | 10.16 | 0.53 |
| 2| 803 | 35.85 | 11.38 | 0.56 |
| 3| 938 | 37.87 | 12.61 | 0.59 |
| 5| 1374 | 43.96 | 15.68 | 0.68 |
| 10| 1974 | 53.42 | 21.61 | 0.82 |
| 29| 5027 | 99.34 | 47.12 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5779 | 27.09 | 9.08 | 0.69 |
| 2| 5957 | 35.99 | 12.09 | 0.79 |
| 3| 6143 | 46.08 | 15.53 | 0.90 |
| 4| 6415 | 56.96 | 19.24 | 1.03 |
| 5| 6206 | 52.44 | 17.46 | 0.97 |
| 6| 6502 | 72.26 | 24.26 | 1.20 |
| 7| 6778 | 84.78 | 28.56 | 1.34 |
| 8| 6856 | 89.28 | 30.04 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.49 | 6.17 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6004 | 28.65 | 10.19 | 0.72 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1709 | 6855 | 79.78 | 30.37 | 1.32 |
| 10 | 39 | 2219 | 7159 | 98.49 | 37.73 | 1.53 |

