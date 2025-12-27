--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-27 04:42:52.66676232 UTC |
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
| 1| 5836 | 10.86 | 3.46 | 0.52 |
| 2| 6035 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.71 | 5.91 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 44.12 | 12.66 | 0.63 |
| 4 | 225 | 858 | 51.01 | 14.66 | 0.71 |
| 5 | 281 | 969 | 58.72 | 16.87 | 0.79 |
| 6 | 337 | 1081 | 74.98 | 21.30 | 0.96 |
| 7 | 393 | 1192 | 82.85 | 23.51 | 1.04 |
| 8 | 451 | 1303 | 83.56 | 24.13 | 1.06 |
| 9 | 504 | 1414 | 95.25 | 27.40 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 22.93 | 7.32 | 0.47 |
| 2| 2002 | 26.50 | 8.99 | 0.52 |
| 3| 2065 | 26.98 | 9.78 | 0.53 |
| 5| 2394 | 31.12 | 12.27 | 0.60 |
| 10| 3191 | 41.78 | 18.58 | 0.76 |
| 42| 7706 | 98.81 | 55.75 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 659 | 22.50 | 7.30 | 0.41 |
| 2| 772 | 23.59 | 8.23 | 0.43 |
| 3| 915 | 25.07 | 9.31 | 0.46 |
| 5| 1260 | 30.70 | 12.25 | 0.54 |
| 10| 2175 | 42.93 | 19.01 | 0.73 |
| 40| 6692 | 98.18 | 54.35 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 27.51 | 8.47 | 0.46 |
| 2| 793 | 30.94 | 10.07 | 0.51 |
| 3| 868 | 32.01 | 11.01 | 0.53 |
| 5| 1379 | 36.02 | 13.55 | 0.60 |
| 10| 1987 | 47.22 | 19.99 | 0.76 |
| 35| 5759 | 95.53 | 50.22 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 33.12 | 9.94 | 0.52 |
| 2| 872 | 36.56 | 11.60 | 0.57 |
| 3| 942 | 37.91 | 12.62 | 0.59 |
| 5| 1392 | 43.98 | 15.69 | 0.68 |
| 10| 2181 | 55.99 | 22.41 | 0.86 |
| 28| 4826 | 96.63 | 45.67 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5781 | 27.00 | 9.06 | 0.69 |
| 2| 5821 | 31.52 | 10.47 | 0.74 |
| 3| 6097 | 45.17 | 15.20 | 0.89 |
| 4| 6242 | 53.92 | 18.12 | 0.99 |
| 5| 6354 | 59.23 | 19.83 | 1.05 |
| 6| 6482 | 70.06 | 23.60 | 1.17 |
| 7| 6790 | 84.47 | 28.52 | 1.34 |
| 8| 6662 | 86.48 | 28.96 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 568 | 6172 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1137 | 6511 | 58.84 | 22.14 | 1.07 |
| 10 | 30 | 1710 | 6857 | 80.22 | 30.52 | 1.32 |
| 10 | 38 | 2161 | 7123 | 97.33 | 37.23 | 1.52 |

