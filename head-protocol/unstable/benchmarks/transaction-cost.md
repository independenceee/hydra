--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-09 04:14:50.035178988 UTC |
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
| 1| 5837 | 10.59 | 3.36 | 0.52 |
| 2| 6037 | 12.54 | 3.97 | 0.55 |
| 3| 6242 | 14.59 | 4.61 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 169 | 747 | 40.38 | 11.75 | 0.59 |
| 4 | 226 | 858 | 51.12 | 14.69 | 0.71 |
| 5 | 282 | 969 | 62.34 | 17.73 | 0.82 |
| 6 | 338 | 1081 | 74.74 | 21.13 | 0.95 |
| 7 | 396 | 1196 | 76.24 | 21.96 | 0.98 |
| 8 | 452 | 1303 | 83.44 | 24.10 | 1.06 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1812 | 24.37 | 7.71 | 0.48 |
| 2| 1995 | 26.58 | 9.01 | 0.52 |
| 3| 2207 | 28.97 | 10.34 | 0.56 |
| 5| 2400 | 30.92 | 12.22 | 0.59 |
| 10| 3152 | 40.86 | 18.32 | 0.75 |
| 40| 7632 | 98.20 | 54.30 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 617 | 22.84 | 7.38 | 0.42 |
| 2| 821 | 25.43 | 8.78 | 0.46 |
| 3| 895 | 25.01 | 9.29 | 0.46 |
| 5| 1226 | 29.04 | 11.76 | 0.52 |
| 10| 2010 | 41.49 | 18.57 | 0.71 |
| 37| 5940 | 92.77 | 50.80 | 1.53 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.54 | 8.47 | 0.46 |
| 2| 801 | 30.94 | 10.07 | 0.51 |
| 3| 944 | 32.72 | 11.23 | 0.54 |
| 5| 1134 | 35.71 | 13.37 | 0.59 |
| 10| 2088 | 45.12 | 19.44 | 0.75 |
| 37| 6084 | 98.71 | 52.50 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 707 | 33.83 | 10.15 | 0.53 |
| 2| 853 | 36.60 | 11.61 | 0.57 |
| 3| 946 | 37.95 | 12.63 | 0.59 |
| 5| 1288 | 43.36 | 15.49 | 0.67 |
| 10| 2059 | 54.92 | 22.08 | 0.84 |
| 29| 4935 | 99.06 | 47.03 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5820 | 27.08 | 9.08 | 0.69 |
| 2| 5876 | 34.95 | 11.70 | 0.78 |
| 3| 6131 | 45.80 | 15.45 | 0.90 |
| 4| 6234 | 52.36 | 17.63 | 0.97 |
| 5| 6423 | 63.79 | 21.46 | 1.10 |
| 6| 6576 | 71.18 | 24.02 | 1.19 |
| 7| 6759 | 83.84 | 28.27 | 1.33 |
| 8| 6753 | 88.79 | 29.84 | 1.38 |
| 9| 6857 | 93.89 | 31.48 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 10 | 568 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 39 | 2218 | 7157 | 98.93 | 37.88 | 1.54 |

