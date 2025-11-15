--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-15 04:21:50.097126926 UTC |
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
| 1| 5837 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.47 | 4.57 | 0.57 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 28.81 | 9.07 | 0.78 |
| 43| 14281 | 99.13 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 170 | 747 | 40.24 | 11.71 | 0.59 |
| 4 | 226 | 858 | 52.42 | 15.00 | 0.72 |
| 5 | 283 | 969 | 61.05 | 17.46 | 0.81 |
| 6 | 339 | 1081 | 71.31 | 20.30 | 0.92 |
| 7 | 394 | 1192 | 72.72 | 21.08 | 0.94 |
| 8 | 448 | 1303 | 91.40 | 25.86 | 1.13 |
| 9 | 505 | 1414 | 89.87 | 26.16 | 1.13 |
| 10 | 561 | 1529 | 98.28 | 28.53 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1983 | 26.92 | 9.08 | 0.52 |
| 3| 2135 | 28.51 | 10.19 | 0.55 |
| 5| 2371 | 31.01 | 12.24 | 0.59 |
| 10| 3205 | 42.01 | 18.64 | 0.77 |
| 39| 7635 | 99.66 | 54.02 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.80 | 7.36 | 0.41 |
| 2| 768 | 23.55 | 8.22 | 0.43 |
| 3| 875 | 25.13 | 9.33 | 0.46 |
| 5| 1227 | 30.02 | 12.03 | 0.53 |
| 10| 1992 | 39.38 | 18.00 | 0.69 |
| 42| 6719 | 98.30 | 55.71 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 646 | 29.13 | 8.90 | 0.48 |
| 2| 779 | 30.90 | 10.06 | 0.51 |
| 3| 1054 | 34.10 | 11.65 | 0.56 |
| 5| 1272 | 35.00 | 13.24 | 0.58 |
| 10| 2013 | 47.43 | 20.04 | 0.77 |
| 36| 5931 | 95.51 | 50.91 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.79 | 10.15 | 0.53 |
| 2| 814 | 35.89 | 11.39 | 0.56 |
| 3| 964 | 37.95 | 12.63 | 0.59 |
| 5| 1299 | 43.28 | 15.47 | 0.67 |
| 10| 1992 | 53.46 | 21.62 | 0.83 |
| 29| 4946 | 98.92 | 46.94 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5787 | 27.16 | 9.10 | 0.69 |
| 2| 5889 | 32.44 | 10.84 | 0.75 |
| 3| 6023 | 41.51 | 13.90 | 0.85 |
| 4| 6216 | 54.10 | 18.18 | 0.99 |
| 5| 6431 | 63.59 | 21.43 | 1.10 |
| 6| 6432 | 72.00 | 24.21 | 1.19 |
| 7| 6876 | 85.63 | 28.96 | 1.35 |
| 8| 6811 | 88.31 | 29.70 | 1.38 |
| 9| 6952 | 99.32 | 33.45 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 5 | 286 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2223 | 7162 | 99.38 | 38.04 | 1.54 |

