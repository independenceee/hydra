--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-31 04:26:39.204172131 UTC |
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
| 1| 5836 | 10.55 | 3.35 | 0.52 |
| 2| 6038 | 12.92 | 4.11 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 43.63 | 12.50 | 0.63 |
| 4 | 225 | 858 | 51.26 | 14.77 | 0.71 |
| 5 | 282 | 969 | 61.09 | 17.50 | 0.81 |
| 6 | 339 | 1081 | 73.57 | 20.85 | 0.94 |
| 7 | 394 | 1192 | 87.51 | 24.72 | 1.09 |
| 8 | 448 | 1303 | 96.26 | 27.12 | 1.18 |
| 9 | 504 | 1418 | 97.76 | 27.82 | 1.20 |
| 10 | 560 | 1525 | 99.24 | 28.63 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 24.37 | 7.71 | 0.48 |
| 2| 1935 | 25.88 | 8.79 | 0.51 |
| 3| 2059 | 26.90 | 9.76 | 0.53 |
| 5| 2337 | 29.92 | 11.94 | 0.58 |
| 10| 3197 | 41.97 | 18.63 | 0.76 |
| 41| 7548 | 95.82 | 54.24 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 22.81 | 7.37 | 0.42 |
| 2| 766 | 23.98 | 8.37 | 0.44 |
| 3| 1003 | 28.13 | 10.18 | 0.50 |
| 5| 1215 | 29.10 | 11.79 | 0.52 |
| 10| 2009 | 39.46 | 18.00 | 0.69 |
| 39| 6458 | 99.49 | 54.04 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 27.50 | 8.46 | 0.46 |
| 2| 786 | 30.98 | 10.08 | 0.51 |
| 3| 960 | 30.98 | 10.76 | 0.52 |
| 5| 1350 | 36.35 | 13.65 | 0.60 |
| 10| 1955 | 46.73 | 19.83 | 0.76 |
| 37| 6035 | 98.81 | 52.47 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 830 | 35.92 | 11.40 | 0.56 |
| 3| 1002 | 38.59 | 12.82 | 0.60 |
| 5| 1381 | 43.96 | 15.68 | 0.68 |
| 10| 2027 | 54.13 | 21.83 | 0.83 |
| 30| 4847 | 98.58 | 47.46 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5834 | 26.92 | 9.05 | 0.69 |
| 2| 6004 | 37.08 | 12.49 | 0.80 |
| 3| 6039 | 43.90 | 14.70 | 0.88 |
| 4| 6367 | 57.46 | 19.45 | 1.03 |
| 5| 6571 | 66.13 | 22.36 | 1.13 |
| 6| 6578 | 72.78 | 24.51 | 1.20 |
| 7| 6880 | 84.99 | 28.74 | 1.35 |
| 8| 6991 | 94.83 | 32.02 | 1.45 |
| 9| 6945 | 99.50 | 33.42 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 10 | 567 | 6171 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1139 | 6513 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1706 | 6852 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2220 | 7159 | 98.49 | 37.73 | 1.53 |

