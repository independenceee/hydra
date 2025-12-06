--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-06 04:22:25.299436656 UTC |
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
| 1| 5836 | 10.48 | 3.33 | 0.52 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 19.02 | 6.02 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 170 | 747 | 42.62 | 12.24 | 0.62 |
| 4 | 227 | 858 | 52.48 | 15.04 | 0.72 |
| 5 | 282 | 969 | 61.05 | 17.49 | 0.81 |
| 6 | 340 | 1081 | 71.40 | 20.33 | 0.92 |
| 7 | 394 | 1192 | 84.53 | 23.91 | 1.06 |
| 8 | 449 | 1303 | 88.67 | 25.24 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.00 | 7.62 | 0.48 |
| 2| 1983 | 26.55 | 9.00 | 0.52 |
| 3| 2074 | 27.77 | 9.99 | 0.54 |
| 5| 2359 | 31.00 | 12.24 | 0.59 |
| 10| 3070 | 39.64 | 17.98 | 0.74 |
| 41| 7491 | 95.55 | 54.17 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 599 | 22.57 | 7.30 | 0.41 |
| 2| 744 | 24.31 | 8.45 | 0.44 |
| 3| 878 | 25.85 | 9.55 | 0.47 |
| 5| 1212 | 29.94 | 12.03 | 0.53 |
| 10| 2018 | 39.62 | 18.05 | 0.69 |
| 41| 6476 | 95.49 | 54.25 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.13 | 8.90 | 0.48 |
| 2| 771 | 28.51 | 9.39 | 0.48 |
| 3| 898 | 30.26 | 10.55 | 0.51 |
| 5| 1267 | 36.91 | 13.75 | 0.60 |
| 10| 2017 | 47.70 | 20.12 | 0.77 |
| 37| 6051 | 97.76 | 52.18 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.15 | 0.53 |
| 2| 873 | 36.52 | 11.59 | 0.57 |
| 3| 1040 | 39.30 | 13.04 | 0.61 |
| 5| 1285 | 42.65 | 15.28 | 0.66 |
| 10| 2029 | 54.72 | 22.01 | 0.84 |
| 30| 4931 | 99.50 | 47.76 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 23.01 | 7.58 | 0.64 |
| 2| 6012 | 36.89 | 12.43 | 0.80 |
| 3| 6094 | 44.85 | 15.05 | 0.89 |
| 4| 6162 | 50.58 | 16.95 | 0.95 |
| 5| 6391 | 60.44 | 20.32 | 1.07 |
| 6| 6512 | 72.05 | 24.20 | 1.19 |
| 7| 6753 | 83.39 | 28.10 | 1.32 |
| 8| 6965 | 94.59 | 31.93 | 1.45 |
| 9| 6988 | 97.10 | 32.65 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6175 | 38.99 | 14.28 | 0.84 |
| 10 | 39 | 2221 | 7161 | 99.82 | 38.19 | 1.55 |

