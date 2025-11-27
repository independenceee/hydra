--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-27 04:34:05.844022992 UTC |
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
| 1| 5837 | 10.35 | 3.28 | 0.51 |
| 2| 6038 | 12.42 | 3.93 | 0.54 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6645 | 18.83 | 5.95 | 0.64 |
| 10| 7646 | 28.90 | 9.10 | 0.79 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2167 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 42.66 | 12.27 | 0.62 |
| 4 | 226 | 858 | 51.12 | 14.69 | 0.71 |
| 5 | 285 | 974 | 57.57 | 16.59 | 0.78 |
| 6 | 338 | 1081 | 69.85 | 19.96 | 0.91 |
| 7 | 394 | 1192 | 77.05 | 22.17 | 0.98 |
| 8 | 453 | 1303 | 96.41 | 27.15 | 1.18 |
| 9 | 504 | 1414 | 96.41 | 27.56 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1814 | 24.37 | 7.71 | 0.48 |
| 2| 1879 | 24.77 | 8.48 | 0.49 |
| 3| 2059 | 27.02 | 9.79 | 0.53 |
| 5| 2468 | 32.94 | 12.77 | 0.62 |
| 10| 3243 | 42.97 | 18.91 | 0.78 |
| 39| 7319 | 93.39 | 52.32 | 1.60 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 654 | 22.81 | 7.38 | 0.42 |
| 2| 827 | 25.37 | 8.75 | 0.45 |
| 3| 915 | 25.10 | 9.32 | 0.46 |
| 5| 1255 | 29.49 | 11.89 | 0.53 |
| 10| 2114 | 41.75 | 18.65 | 0.72 |
| 40| 6514 | 98.07 | 54.32 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 659 | 29.17 | 8.91 | 0.48 |
| 2| 813 | 29.19 | 9.60 | 0.49 |
| 3| 911 | 32.68 | 11.22 | 0.54 |
| 5| 1272 | 34.97 | 13.23 | 0.58 |
| 10| 2029 | 44.90 | 19.37 | 0.74 |
| 35| 5674 | 98.60 | 51.04 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.87 | 10.16 | 0.53 |
| 2| 799 | 35.81 | 11.37 | 0.56 |
| 3| 937 | 37.84 | 12.60 | 0.59 |
| 5| 1209 | 41.82 | 15.03 | 0.65 |
| 10| 2146 | 55.36 | 22.21 | 0.85 |
| 29| 4791 | 97.90 | 46.67 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5799 | 27.00 | 9.06 | 0.69 |
| 2| 5996 | 37.01 | 12.48 | 0.80 |
| 3| 5970 | 40.35 | 13.47 | 0.84 |
| 4| 6306 | 55.00 | 18.52 | 1.01 |
| 5| 6491 | 66.67 | 22.60 | 1.14 |
| 6| 6618 | 73.84 | 24.93 | 1.22 |
| 7| 6523 | 75.61 | 25.36 | 1.23 |
| 8| 6899 | 90.55 | 30.46 | 1.40 |
| 9| 6976 | 98.41 | 33.04 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 56 | 5867 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 569 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2218 | 7157 | 97.61 | 37.43 | 1.52 |

