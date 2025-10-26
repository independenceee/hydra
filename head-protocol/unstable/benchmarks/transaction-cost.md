--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-26 04:15:53.600665613 UTC |
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
| 2| 6038 | 12.42 | 3.93 | 0.54 |
| 3| 6238 | 14.40 | 4.55 | 0.57 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 99.02 | 30.95 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 170 | 747 | 42.37 | 12.20 | 0.61 |
| 4 | 227 | 858 | 51.17 | 14.72 | 0.71 |
| 5 | 284 | 969 | 58.20 | 16.84 | 0.78 |
| 6 | 337 | 1085 | 70.05 | 20.04 | 0.91 |
| 7 | 394 | 1192 | 86.89 | 24.48 | 1.08 |
| 8 | 450 | 1307 | 96.26 | 27.17 | 1.18 |
| 9 | 504 | 1414 | 91.90 | 26.43 | 1.15 |
| 10 | 560 | 1525 | 98.64 | 28.56 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.00 | 7.62 | 0.48 |
| 2| 1987 | 26.62 | 9.02 | 0.52 |
| 3| 2063 | 27.24 | 9.84 | 0.53 |
| 5| 2470 | 33.14 | 12.84 | 0.62 |
| 10| 3197 | 40.68 | 18.27 | 0.75 |
| 41| 7648 | 96.75 | 54.54 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.84 | 7.38 | 0.41 |
| 2| 791 | 24.28 | 8.45 | 0.44 |
| 3| 1001 | 28.07 | 10.17 | 0.49 |
| 5| 1093 | 27.04 | 11.20 | 0.50 |
| 10| 2000 | 39.83 | 18.12 | 0.69 |
| 41| 6685 | 99.67 | 55.44 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.17 | 8.91 | 0.48 |
| 2| 893 | 29.90 | 9.82 | 0.50 |
| 3| 910 | 32.76 | 11.24 | 0.54 |
| 5| 1227 | 37.10 | 13.80 | 0.60 |
| 10| 2036 | 44.90 | 19.37 | 0.74 |
| 36| 6021 | 98.88 | 51.88 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.83 | 10.15 | 0.53 |
| 2| 844 | 36.64 | 11.62 | 0.57 |
| 3| 953 | 37.84 | 12.60 | 0.59 |
| 5| 1201 | 41.90 | 15.05 | 0.65 |
| 10| 2038 | 54.84 | 22.04 | 0.84 |
| 30| 4982 | 98.88 | 47.59 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5818 | 26.96 | 9.05 | 0.69 |
| 2| 6019 | 36.93 | 12.45 | 0.80 |
| 3| 6134 | 45.98 | 15.51 | 0.90 |
| 4| 6181 | 50.31 | 16.88 | 0.95 |
| 5| 6451 | 63.13 | 21.29 | 1.10 |
| 6| 6585 | 74.72 | 25.20 | 1.23 |
| 7| 6816 | 84.17 | 28.43 | 1.34 |
| 8| 7019 | 95.12 | 32.15 | 1.46 |
| 9| 6754 | 85.93 | 28.71 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 22.99 | 7.82 | 0.65 |
| 10 | 5 | 284 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 567 | 6172 | 40.83 | 14.90 | 0.86 |
| 10 | 20 | 1138 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 39 | 2215 | 7155 | 98.93 | 37.88 | 1.54 |

