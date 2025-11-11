--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-11 04:34:42.901340705 UTC |
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
| 1| 5834 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.78 | 4.06 | 0.55 |
| 3| 6238 | 14.98 | 4.75 | 0.58 |
| 5| 6641 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 99.49 | 31.12 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 170 | 747 | 41.07 | 11.87 | 0.60 |
| 4 | 225 | 858 | 52.55 | 15.06 | 0.72 |
| 5 | 281 | 969 | 60.90 | 17.42 | 0.81 |
| 6 | 337 | 1085 | 73.24 | 20.81 | 0.94 |
| 7 | 392 | 1192 | 84.90 | 24.04 | 1.06 |
| 8 | 452 | 1303 | 81.72 | 23.63 | 1.04 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1821 | 24.37 | 7.71 | 0.48 |
| 2| 1997 | 26.42 | 8.96 | 0.52 |
| 3| 2013 | 26.24 | 9.56 | 0.52 |
| 5| 2512 | 33.57 | 12.94 | 0.63 |
| 10| 3231 | 42.85 | 18.88 | 0.77 |
| 39| 7316 | 94.16 | 52.44 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 664 | 22.54 | 7.31 | 0.41 |
| 2| 767 | 23.61 | 8.25 | 0.43 |
| 3| 942 | 26.86 | 9.84 | 0.48 |
| 5| 1210 | 30.02 | 12.05 | 0.53 |
| 10| 2044 | 39.44 | 18.01 | 0.69 |
| 39| 6423 | 99.63 | 54.03 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 26.83 | 8.26 | 0.45 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 995 | 31.65 | 10.97 | 0.53 |
| 5| 1274 | 37.85 | 14.02 | 0.61 |
| 10| 2046 | 47.81 | 20.17 | 0.77 |
| 35| 5734 | 95.04 | 50.08 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 33.87 | 10.16 | 0.53 |
| 2| 806 | 35.88 | 11.39 | 0.56 |
| 3| 895 | 37.24 | 12.41 | 0.58 |
| 5| 1209 | 41.93 | 15.06 | 0.65 |
| 10| 2127 | 55.52 | 22.25 | 0.85 |
| 30| 4965 | 98.67 | 47.52 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5821 | 26.92 | 9.05 | 0.69 |
| 2| 5984 | 36.89 | 12.42 | 0.80 |
| 3| 5991 | 43.65 | 14.62 | 0.87 |
| 4| 6387 | 57.37 | 19.41 | 1.03 |
| 5| 6289 | 60.52 | 20.33 | 1.06 |
| 6| 6583 | 74.17 | 25.04 | 1.22 |
| 7| 6515 | 76.58 | 25.69 | 1.24 |
| 8| 7028 | 91.04 | 30.73 | 1.42 |
| 9| 6908 | 98.44 | 33.12 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 5 | 285 | 6004 | 30.67 | 10.88 | 0.74 |
| 10 | 30 | 1708 | 6854 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2219 | 7158 | 98.49 | 37.73 | 1.53 |

