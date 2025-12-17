--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-17 04:44:03.203851785 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6643 | 18.90 | 5.97 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 169 | 747 | 41.29 | 11.92 | 0.60 |
| 4 | 227 | 858 | 53.63 | 15.27 | 0.73 |
| 5 | 281 | 974 | 56.37 | 16.31 | 0.77 |
| 6 | 338 | 1081 | 68.61 | 19.74 | 0.89 |
| 7 | 394 | 1192 | 76.91 | 22.09 | 0.98 |
| 8 | 448 | 1303 | 84.49 | 24.39 | 1.07 |
| 9 | 504 | 1414 | 98.54 | 28.01 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1828 | 24.37 | 7.71 | 0.48 |
| 2| 1883 | 24.47 | 8.41 | 0.49 |
| 3| 2134 | 27.86 | 10.03 | 0.54 |
| 5| 2366 | 30.96 | 12.23 | 0.59 |
| 10| 3253 | 42.81 | 18.87 | 0.78 |
| 41| 7854 | 99.13 | 55.25 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.50 | 7.29 | 0.41 |
| 2| 759 | 24.05 | 8.39 | 0.44 |
| 3| 930 | 26.67 | 9.80 | 0.48 |
| 5| 1214 | 30.00 | 12.05 | 0.53 |
| 10| 1932 | 38.11 | 17.64 | 0.67 |
| 41| 6673 | 98.80 | 55.20 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 27.47 | 8.46 | 0.46 |
| 2| 866 | 29.89 | 9.82 | 0.50 |
| 3| 910 | 32.76 | 11.24 | 0.54 |
| 5| 1294 | 37.85 | 14.02 | 0.61 |
| 10| 2107 | 48.52 | 20.39 | 0.78 |
| 37| 5991 | 96.98 | 51.97 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.12 | 9.94 | 0.52 |
| 2| 764 | 35.21 | 11.18 | 0.55 |
| 3| 896 | 37.13 | 12.38 | 0.58 |
| 5| 1319 | 43.43 | 15.51 | 0.67 |
| 10| 2178 | 55.41 | 22.22 | 0.85 |
| 28| 4668 | 95.16 | 45.22 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.00 | 9.07 | 0.69 |
| 2| 6006 | 36.85 | 12.42 | 0.80 |
| 3| 6149 | 47.04 | 15.85 | 0.92 |
| 4| 6231 | 51.14 | 17.19 | 0.96 |
| 5| 6323 | 59.83 | 20.14 | 1.06 |
| 6| 6381 | 65.50 | 21.92 | 1.12 |
| 7| 6832 | 84.43 | 28.62 | 1.34 |
| 8| 7091 | 94.94 | 32.13 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 283 | 6002 | 29.53 | 10.50 | 0.73 |
| 10 | 20 | 1138 | 6512 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1707 | 6853 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2160 | 7122 | 96.88 | 37.08 | 1.51 |

