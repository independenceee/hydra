--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-09-25 03:47:42.799038128 UTC |
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
| 1| 5836 | 10.76 | 3.42 | 0.52 |
| 2| 6038 | 12.70 | 4.03 | 0.55 |
| 3| 6238 | 14.69 | 4.65 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 170 | 751 | 39.97 | 11.62 | 0.59 |
| 4 | 226 | 858 | 48.12 | 14.02 | 0.68 |
| 5 | 284 | 969 | 62.87 | 17.92 | 0.83 |
| 6 | 339 | 1081 | 66.89 | 19.40 | 0.88 |
| 7 | 393 | 1192 | 87.32 | 24.71 | 1.09 |
| 8 | 448 | 1303 | 87.70 | 25.07 | 1.10 |
| 9 | 504 | 1414 | 96.59 | 27.65 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1746 | 22.92 | 7.32 | 0.47 |
| 2| 1883 | 24.77 | 8.48 | 0.49 |
| 3| 2120 | 27.94 | 10.05 | 0.54 |
| 5| 2324 | 30.08 | 11.98 | 0.58 |
| 10| 3214 | 41.81 | 18.59 | 0.76 |
| 39| 7566 | 97.41 | 53.38 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.54 | 7.30 | 0.41 |
| 2| 865 | 25.57 | 8.81 | 0.46 |
| 3| 861 | 23.99 | 9.01 | 0.45 |
| 5| 1137 | 28.87 | 11.73 | 0.52 |
| 10| 2182 | 43.21 | 19.07 | 0.73 |
| 41| 6616 | 97.34 | 54.79 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 661 | 29.17 | 8.91 | 0.48 |
| 2| 868 | 29.90 | 9.82 | 0.50 |
| 3| 1091 | 32.36 | 11.19 | 0.54 |
| 5| 1193 | 36.31 | 13.56 | 0.59 |
| 10| 1995 | 44.33 | 19.19 | 0.73 |
| 36| 6045 | 98.51 | 51.75 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 879 | 36.64 | 11.62 | 0.57 |
| 3| 954 | 37.84 | 12.60 | 0.59 |
| 5| 1272 | 42.53 | 15.25 | 0.66 |
| 10| 2189 | 56.05 | 22.42 | 0.86 |
| 29| 5025 | 99.23 | 47.07 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5787 | 27.09 | 9.08 | 0.69 |
| 2| 5952 | 35.96 | 12.07 | 0.79 |
| 3| 6233 | 46.73 | 15.82 | 0.92 |
| 4| 6381 | 56.45 | 19.07 | 1.02 |
| 5| 6283 | 59.68 | 20.00 | 1.05 |
| 6| 6572 | 71.43 | 24.10 | 1.19 |
| 7| 6684 | 79.60 | 26.80 | 1.28 |
| 8| 6776 | 89.03 | 29.94 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.08 | 6.83 | 0.62 |
| 10 | 5 | 283 | 6002 | 27.58 | 9.82 | 0.71 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1705 | 6852 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2275 | 7191 | 99.66 | 38.24 | 1.55 |

