--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-17 04:42:15.634076602 UTC |
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
| 1| 5834 | 10.76 | 3.42 | 0.52 |
| 2| 6035 | 12.53 | 3.97 | 0.55 |
| 3| 6240 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7644 | 28.73 | 9.04 | 0.78 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 112 | 636 | 33.40 | 9.67 | 0.52 |
| 3 | 170 | 747 | 42.61 | 12.28 | 0.62 |
| 4 | 227 | 858 | 49.13 | 14.23 | 0.69 |
| 5 | 285 | 969 | 61.22 | 17.53 | 0.81 |
| 6 | 340 | 1081 | 73.78 | 20.94 | 0.94 |
| 7 | 394 | 1192 | 84.80 | 24.02 | 1.06 |
| 8 | 450 | 1303 | 92.96 | 26.23 | 1.15 |
| 10 | 560 | 1529 | 99.68 | 28.74 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1808 | 24.00 | 7.62 | 0.48 |
| 2| 1883 | 24.77 | 8.48 | 0.49 |
| 3| 2189 | 29.26 | 10.41 | 0.56 |
| 5| 2323 | 30.26 | 12.02 | 0.58 |
| 10| 3136 | 40.66 | 18.27 | 0.75 |
| 41| 7755 | 99.40 | 55.26 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.84 | 7.38 | 0.41 |
| 2| 723 | 22.60 | 7.95 | 0.42 |
| 3| 988 | 28.24 | 10.23 | 0.50 |
| 5| 1335 | 33.01 | 12.89 | 0.57 |
| 10| 2099 | 43.54 | 19.12 | 0.73 |
| 40| 6521 | 96.80 | 53.97 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 29.13 | 8.90 | 0.48 |
| 2| 736 | 30.27 | 9.86 | 0.50 |
| 3| 979 | 30.82 | 10.73 | 0.52 |
| 5| 1338 | 35.68 | 13.45 | 0.59 |
| 10| 2084 | 45.38 | 19.53 | 0.75 |
| 35| 5834 | 96.62 | 50.55 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.83 | 10.15 | 0.53 |
| 2| 806 | 35.85 | 11.38 | 0.56 |
| 3| 994 | 38.63 | 12.83 | 0.60 |
| 5| 1200 | 42.01 | 15.08 | 0.65 |
| 10| 2161 | 55.85 | 22.35 | 0.86 |
| 29| 4736 | 96.44 | 46.24 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5795 | 26.97 | 9.06 | 0.69 |
| 2| 5820 | 31.60 | 10.51 | 0.74 |
| 3| 6166 | 45.79 | 15.46 | 0.90 |
| 4| 6260 | 54.89 | 18.51 | 1.00 |
| 5| 6333 | 60.92 | 20.47 | 1.07 |
| 6| 6563 | 73.32 | 24.71 | 1.21 |
| 7| 6851 | 85.49 | 28.96 | 1.35 |
| 8| 6750 | 84.06 | 28.12 | 1.33 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 569 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6854 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2222 | 7162 | 97.61 | 37.43 | 1.52 |

