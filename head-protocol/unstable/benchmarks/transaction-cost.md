--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-05 04:15:06.702617036 UTC |
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
| 1| 5837 | 10.61 | 3.37 | 0.52 |
| 2| 6035 | 12.41 | 3.92 | 0.54 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6645 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 41.46 | 11.98 | 0.60 |
| 4 | 228 | 858 | 53.85 | 15.34 | 0.73 |
| 5 | 284 | 969 | 62.85 | 17.89 | 0.83 |
| 6 | 340 | 1081 | 75.76 | 21.41 | 0.96 |
| 7 | 395 | 1196 | 82.49 | 23.42 | 1.04 |
| 8 | 449 | 1303 | 92.16 | 26.24 | 1.14 |
| 9 | 506 | 1414 | 91.28 | 26.38 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1796 | 24.00 | 7.62 | 0.48 |
| 2| 1945 | 25.51 | 8.70 | 0.50 |
| 3| 2059 | 26.94 | 9.77 | 0.53 |
| 5| 2411 | 31.76 | 12.44 | 0.60 |
| 10| 3092 | 40.35 | 18.17 | 0.74 |
| 38| 7448 | 96.91 | 52.57 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 22.84 | 7.39 | 0.41 |
| 2| 745 | 23.62 | 8.24 | 0.43 |
| 3| 1017 | 27.97 | 10.14 | 0.49 |
| 5| 1170 | 28.12 | 11.50 | 0.51 |
| 10| 1978 | 38.68 | 17.78 | 0.68 |
| 39| 6613 | 98.06 | 53.66 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.17 | 8.91 | 0.48 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 999 | 34.11 | 11.65 | 0.55 |
| 5| 1267 | 37.66 | 13.97 | 0.61 |
| 10| 2033 | 44.93 | 19.38 | 0.74 |
| 36| 5839 | 94.46 | 50.59 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.87 | 10.16 | 0.53 |
| 2| 859 | 36.64 | 11.62 | 0.57 |
| 3| 995 | 38.59 | 12.82 | 0.60 |
| 5| 1207 | 41.97 | 15.07 | 0.65 |
| 10| 2081 | 54.85 | 22.04 | 0.84 |
| 30| 4965 | 99.93 | 47.91 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5810 | 27.13 | 9.09 | 0.69 |
| 2| 5942 | 35.84 | 12.04 | 0.79 |
| 3| 5945 | 40.48 | 13.50 | 0.84 |
| 4| 6262 | 55.06 | 18.53 | 1.00 |
| 5| 6311 | 59.41 | 19.89 | 1.05 |
| 6| 6785 | 76.77 | 25.93 | 1.26 |
| 7| 6696 | 82.66 | 27.81 | 1.31 |
| 8| 6888 | 90.35 | 30.55 | 1.40 |
| 9| 6938 | 98.73 | 33.23 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1139 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6853 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2279 | 7196 | 99.22 | 38.09 | 1.54 |

