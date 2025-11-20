--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-20 04:31:58.852508789 UTC |
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
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6236 | 15.16 | 4.82 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7644 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 169 | 747 | 42.53 | 12.22 | 0.61 |
| 4 | 227 | 858 | 51.14 | 14.72 | 0.71 |
| 5 | 282 | 969 | 64.43 | 18.30 | 0.85 |
| 6 | 338 | 1081 | 65.81 | 18.99 | 0.87 |
| 7 | 393 | 1192 | 74.43 | 21.49 | 0.96 |
| 8 | 450 | 1303 | 89.82 | 25.63 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1818 | 24.00 | 7.62 | 0.48 |
| 2| 1942 | 25.88 | 8.79 | 0.51 |
| 3| 2085 | 27.40 | 9.88 | 0.53 |
| 5| 2381 | 31.37 | 12.33 | 0.60 |
| 10| 3123 | 41.01 | 18.35 | 0.75 |
| 39| 7554 | 97.31 | 53.35 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 22.81 | 7.37 | 0.42 |
| 2| 744 | 24.00 | 8.39 | 0.44 |
| 3| 921 | 25.72 | 9.52 | 0.47 |
| 5| 1384 | 32.98 | 12.88 | 0.57 |
| 10| 2093 | 40.63 | 18.34 | 0.70 |
| 41| 6621 | 98.14 | 55.02 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.83 | 8.26 | 0.45 |
| 2| 834 | 29.19 | 9.60 | 0.49 |
| 3| 1006 | 31.53 | 10.94 | 0.53 |
| 5| 1250 | 37.02 | 13.77 | 0.60 |
| 10| 2090 | 47.96 | 20.21 | 0.78 |
| 35| 5767 | 93.88 | 49.77 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 33.87 | 10.16 | 0.53 |
| 2| 819 | 35.92 | 11.40 | 0.56 |
| 3| 938 | 37.95 | 12.63 | 0.59 |
| 5| 1337 | 43.40 | 15.50 | 0.67 |
| 10| 2164 | 56.12 | 22.44 | 0.86 |
| 29| 4765 | 97.86 | 46.64 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5780 | 27.00 | 9.06 | 0.69 |
| 2| 5975 | 35.99 | 12.09 | 0.79 |
| 3| 6107 | 45.80 | 15.44 | 0.90 |
| 4| 6164 | 52.49 | 17.66 | 0.97 |
| 5| 6504 | 65.50 | 22.09 | 1.12 |
| 6| 6551 | 73.32 | 24.68 | 1.21 |
| 7| 6608 | 78.74 | 26.47 | 1.27 |
| 8| 6854 | 94.21 | 31.82 | 1.44 |
| 9| 6792 | 95.42 | 31.96 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 284 | 6003 | 29.79 | 10.58 | 0.73 |
| 10 | 20 | 1139 | 6513 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2217 | 7157 | 98.05 | 37.58 | 1.53 |

