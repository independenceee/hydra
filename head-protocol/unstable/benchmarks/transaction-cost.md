--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-31 04:49:25.290648122 UTC |
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
| 2| 6035 | 12.61 | 4.00 | 0.55 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 40.21 | 11.69 | 0.59 |
| 4 | 227 | 858 | 54.08 | 15.42 | 0.74 |
| 5 | 281 | 969 | 59.35 | 17.05 | 0.80 |
| 6 | 338 | 1081 | 69.68 | 19.88 | 0.90 |
| 7 | 395 | 1192 | 74.27 | 21.37 | 0.96 |
| 8 | 451 | 1303 | 85.21 | 24.52 | 1.07 |
| 9 | 505 | 1414 | 98.63 | 28.14 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1809 | 24.37 | 7.71 | 0.48 |
| 2| 1921 | 25.39 | 8.68 | 0.50 |
| 3| 2014 | 26.32 | 9.58 | 0.52 |
| 5| 2275 | 28.96 | 11.67 | 0.57 |
| 10| 3054 | 39.02 | 17.81 | 0.73 |
| 41| 7521 | 95.95 | 54.31 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 662 | 22.81 | 7.38 | 0.42 |
| 2| 699 | 22.58 | 7.96 | 0.42 |
| 3| 940 | 27.10 | 9.89 | 0.48 |
| 5| 1222 | 30.05 | 12.05 | 0.53 |
| 10| 1950 | 39.80 | 18.12 | 0.69 |
| 43| 6759 | 98.78 | 56.50 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 29.13 | 8.90 | 0.48 |
| 2| 781 | 30.98 | 10.08 | 0.51 |
| 3| 959 | 30.94 | 10.75 | 0.52 |
| 5| 1126 | 35.64 | 13.36 | 0.58 |
| 10| 1888 | 45.87 | 19.57 | 0.75 |
| 39| 6189 | 99.99 | 54.09 | 1.62 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 33.83 | 10.15 | 0.53 |
| 2| 845 | 36.60 | 11.61 | 0.57 |
| 3| 892 | 37.24 | 12.41 | 0.58 |
| 5| 1200 | 42.01 | 15.08 | 0.65 |
| 10| 2117 | 55.63 | 22.28 | 0.85 |
| 30| 4969 | 99.24 | 47.68 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5815 | 26.92 | 9.04 | 0.69 |
| 2| 5903 | 32.45 | 10.85 | 0.75 |
| 3| 6081 | 46.21 | 15.56 | 0.90 |
| 4| 6333 | 55.91 | 18.90 | 1.02 |
| 5| 6422 | 61.45 | 20.68 | 1.08 |
| 6| 6438 | 68.15 | 22.87 | 1.15 |
| 7| 6851 | 84.03 | 28.32 | 1.33 |
| 8| 6922 | 94.32 | 31.81 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 285 | 6004 | 29.46 | 10.47 | 0.73 |
| 10 | 10 | 568 | 6172 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.91 | 22.51 | 1.08 |
| 10 | 38 | 2162 | 7124 | 96.19 | 36.84 | 1.51 |

