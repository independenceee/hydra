--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-20 04:28:50.405831732 UTC |
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
| 1| 5834 | 11.02 | 3.52 | 0.52 |
| 2| 6037 | 12.70 | 4.03 | 0.55 |
| 3| 6240 | 14.60 | 4.62 | 0.58 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 29.02 | 9.14 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 528 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 43.72 | 12.52 | 0.63 |
| 4 | 227 | 858 | 49.06 | 14.17 | 0.69 |
| 5 | 283 | 969 | 57.98 | 16.78 | 0.78 |
| 6 | 337 | 1081 | 71.98 | 20.58 | 0.93 |
| 7 | 394 | 1192 | 85.02 | 24.03 | 1.06 |
| 8 | 452 | 1303 | 92.48 | 26.27 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1791 | 24.29 | 7.69 | 0.48 |
| 2| 1950 | 25.55 | 8.71 | 0.51 |
| 3| 2116 | 28.10 | 10.09 | 0.54 |
| 5| 2372 | 31.41 | 12.34 | 0.60 |
| 10| 3215 | 41.70 | 18.56 | 0.76 |
| 40| 7614 | 99.05 | 54.49 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 22.77 | 7.36 | 0.42 |
| 2| 765 | 23.59 | 8.23 | 0.43 |
| 3| 911 | 25.07 | 9.31 | 0.46 |
| 5| 1236 | 30.06 | 12.06 | 0.53 |
| 10| 2100 | 42.04 | 18.73 | 0.72 |
| 44| 6785 | 98.51 | 57.08 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.47 | 8.46 | 0.46 |
| 2| 779 | 30.94 | 10.07 | 0.51 |
| 3| 932 | 32.80 | 11.25 | 0.54 |
| 5| 1320 | 35.76 | 13.47 | 0.59 |
| 10| 2107 | 46.12 | 19.75 | 0.76 |
| 36| 5984 | 97.83 | 51.53 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 33.83 | 10.16 | 0.53 |
| 2| 808 | 35.88 | 11.39 | 0.56 |
| 3| 964 | 37.91 | 12.62 | 0.59 |
| 5| 1332 | 43.36 | 15.49 | 0.67 |
| 10| 2072 | 54.85 | 22.04 | 0.84 |
| 29| 4972 | 99.95 | 47.27 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5795 | 26.97 | 9.07 | 0.69 |
| 2| 5918 | 32.53 | 10.86 | 0.75 |
| 3| 6115 | 44.91 | 15.11 | 0.89 |
| 4| 6268 | 52.02 | 17.54 | 0.97 |
| 5| 6332 | 58.00 | 19.56 | 1.04 |
| 6| 6673 | 74.96 | 25.30 | 1.23 |
| 7| 6651 | 79.24 | 26.58 | 1.27 |
| 8| 6827 | 86.18 | 29.04 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 285 | 6005 | 30.23 | 10.73 | 0.74 |
| 10 | 20 | 1138 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1711 | 6857 | 78.71 | 30.00 | 1.30 |
| 10 | 40 | 2280 | 7196 | 99.66 | 38.24 | 1.55 |

