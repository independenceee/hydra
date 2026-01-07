--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-07 04:51:16.664271269 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.63 | 4.00 | 0.55 |
| 3| 6243 | 14.90 | 4.72 | 0.58 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 915 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 43.68 | 12.51 | 0.63 |
| 4 | 226 | 858 | 48.28 | 14.04 | 0.68 |
| 5 | 281 | 969 | 62.62 | 17.83 | 0.83 |
| 6 | 339 | 1081 | 75.43 | 21.33 | 0.96 |
| 7 | 394 | 1196 | 80.14 | 22.77 | 1.01 |
| 8 | 451 | 1303 | 94.60 | 26.82 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 24.37 | 7.71 | 0.48 |
| 2| 1924 | 25.47 | 8.70 | 0.50 |
| 3| 2013 | 26.31 | 9.58 | 0.52 |
| 5| 2412 | 32.23 | 12.58 | 0.61 |
| 10| 3086 | 39.23 | 17.88 | 0.73 |
| 39| 7488 | 97.86 | 53.47 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.81 | 7.37 | 0.42 |
| 2| 843 | 25.37 | 8.76 | 0.46 |
| 3| 834 | 24.13 | 9.05 | 0.45 |
| 5| 1349 | 31.92 | 12.59 | 0.56 |
| 10| 2102 | 42.09 | 18.73 | 0.72 |
| 42| 6571 | 95.03 | 54.82 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.54 | 8.47 | 0.46 |
| 2| 778 | 30.91 | 10.06 | 0.51 |
| 3| 918 | 32.68 | 11.22 | 0.54 |
| 5| 1253 | 34.97 | 13.23 | 0.58 |
| 10| 2047 | 44.96 | 19.38 | 0.74 |
| 35| 5767 | 98.75 | 51.08 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 838 | 36.14 | 11.47 | 0.56 |
| 3| 1029 | 38.66 | 12.84 | 0.60 |
| 5| 1391 | 44.07 | 15.71 | 0.68 |
| 10| 2133 | 55.71 | 22.30 | 0.85 |
| 29| 4815 | 98.16 | 46.71 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 26.97 | 9.07 | 0.69 |
| 2| 5845 | 31.52 | 10.48 | 0.74 |
| 3| 6155 | 45.60 | 15.41 | 0.90 |
| 4| 6261 | 55.07 | 18.58 | 1.00 |
| 5| 6356 | 62.91 | 21.12 | 1.09 |
| 6| 6537 | 69.95 | 23.61 | 1.17 |
| 7| 6701 | 76.79 | 25.80 | 1.25 |
| 8| 6942 | 92.08 | 31.08 | 1.42 |
| 10| 6892 | 99.85 | 33.53 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 10 | 569 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 40 | 2278 | 7194 | 99.22 | 38.09 | 1.54 |

