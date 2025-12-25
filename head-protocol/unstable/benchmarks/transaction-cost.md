--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-25 04:47:47.190443624 UTC |
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
| 2| 6039 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.59 | 4.61 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 29.49 | 9.31 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 170 | 747 | 43.59 | 12.49 | 0.63 |
| 4 | 227 | 858 | 48.31 | 14.01 | 0.68 |
| 5 | 283 | 969 | 61.23 | 17.53 | 0.81 |
| 6 | 340 | 1081 | 65.55 | 18.92 | 0.86 |
| 7 | 395 | 1192 | 86.70 | 24.43 | 1.08 |
| 8 | 450 | 1303 | 91.81 | 26.00 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1808 | 24.29 | 7.69 | 0.48 |
| 2| 1948 | 25.92 | 8.80 | 0.51 |
| 3| 2084 | 27.35 | 9.87 | 0.53 |
| 5| 2318 | 30.34 | 12.04 | 0.58 |
| 10| 3103 | 40.50 | 18.21 | 0.75 |
| 41| 7600 | 97.67 | 54.78 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 607 | 22.57 | 7.30 | 0.41 |
| 2| 812 | 25.13 | 8.69 | 0.45 |
| 3| 828 | 24.06 | 9.02 | 0.45 |
| 5| 1239 | 29.90 | 12.02 | 0.53 |
| 10| 1964 | 39.84 | 18.11 | 0.69 |
| 40| 6313 | 94.01 | 53.17 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 27.50 | 8.46 | 0.46 |
| 2| 816 | 29.22 | 9.61 | 0.49 |
| 3| 952 | 30.90 | 10.74 | 0.52 |
| 5| 1187 | 36.31 | 13.56 | 0.59 |
| 10| 2143 | 49.49 | 20.67 | 0.79 |
| 36| 5703 | 93.38 | 50.24 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 883 | 36.64 | 11.62 | 0.57 |
| 3| 1078 | 39.26 | 13.03 | 0.61 |
| 5| 1261 | 42.53 | 15.25 | 0.66 |
| 10| 2062 | 54.92 | 22.06 | 0.84 |
| 28| 4609 | 95.02 | 45.19 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5811 | 27.00 | 9.08 | 0.69 |
| 2| 5960 | 35.72 | 12.00 | 0.79 |
| 3| 6218 | 46.57 | 15.77 | 0.91 |
| 4| 6348 | 55.60 | 18.80 | 1.01 |
| 5| 6169 | 55.07 | 18.36 | 1.00 |
| 6| 6657 | 76.18 | 25.75 | 1.24 |
| 7| 6674 | 82.33 | 27.71 | 1.31 |
| 8| 6780 | 91.31 | 30.67 | 1.41 |
| 9| 7018 | 99.52 | 33.48 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.49 | 6.17 | 0.60 |
| 10 | 1 | 56 | 5867 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6174 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1135 | 6509 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1712 | 6858 | 79.78 | 30.37 | 1.32 |
| 10 | 38 | 2164 | 7126 | 95.56 | 36.62 | 1.50 |

