--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-09-28 04:16:12.044531937 UTC |
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
| 1| 5834 | 10.55 | 3.35 | 0.52 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.90 | 5.97 | 0.64 |
| 10| 7646 | 29.11 | 9.17 | 0.79 |
| 43| 14281 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1284 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 43.61 | 12.48 | 0.63 |
| 4 | 226 | 858 | 51.12 | 14.69 | 0.71 |
| 5 | 283 | 969 | 63.94 | 18.12 | 0.84 |
| 6 | 339 | 1081 | 74.98 | 21.18 | 0.96 |
| 7 | 393 | 1192 | 72.91 | 21.17 | 0.94 |
| 8 | 450 | 1303 | 92.46 | 26.26 | 1.14 |
| 9 | 507 | 1414 | 96.65 | 27.67 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1783 | 24.37 | 7.71 | 0.48 |
| 2| 1886 | 24.48 | 8.42 | 0.49 |
| 3| 2018 | 26.02 | 9.51 | 0.52 |
| 5| 2480 | 33.31 | 12.88 | 0.62 |
| 10| 3141 | 40.89 | 18.32 | 0.75 |
| 39| 7508 | 97.02 | 53.25 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 22.84 | 7.38 | 0.42 |
| 2| 828 | 25.48 | 8.78 | 0.46 |
| 3| 956 | 27.10 | 9.91 | 0.48 |
| 5| 1222 | 29.12 | 11.78 | 0.52 |
| 10| 1949 | 37.64 | 17.49 | 0.67 |
| 41| 6538 | 95.86 | 54.39 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.83 | 8.26 | 0.45 |
| 2| 842 | 29.15 | 9.59 | 0.49 |
| 3| 927 | 32.72 | 11.23 | 0.54 |
| 5| 1265 | 35.08 | 13.26 | 0.58 |
| 10| 2007 | 44.94 | 19.38 | 0.74 |
| 35| 5464 | 91.73 | 49.06 | 1.49 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 33.87 | 10.16 | 0.53 |
| 2| 884 | 36.52 | 11.59 | 0.57 |
| 3| 1064 | 39.30 | 13.04 | 0.61 |
| 5| 1293 | 43.25 | 15.47 | 0.67 |
| 10| 2023 | 54.25 | 21.86 | 0.84 |
| 28| 5047 | 98.81 | 46.34 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5837 | 26.96 | 9.06 | 0.69 |
| 2| 5957 | 35.84 | 12.04 | 0.79 |
| 3| 6106 | 45.87 | 15.44 | 0.90 |
| 4| 6176 | 51.37 | 17.25 | 0.96 |
| 5| 6415 | 63.03 | 21.14 | 1.09 |
| 6| 6647 | 76.92 | 25.95 | 1.25 |
| 7| 6830 | 85.00 | 28.71 | 1.34 |
| 8| 6881 | 93.80 | 31.66 | 1.44 |
| 9| 6789 | 91.06 | 30.63 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 22.55 | 7.67 | 0.65 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1138 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1710 | 6857 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2159 | 7121 | 96.88 | 37.08 | 1.51 |

