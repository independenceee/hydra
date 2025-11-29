--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-29 04:31:40.312631952 UTC |
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
| 1| 5836 | 10.47 | 3.32 | 0.52 |
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 14.78 | 4.68 | 0.58 |
| 5| 6641 | 18.58 | 5.86 | 0.63 |
| 10| 7647 | 29.23 | 9.22 | 0.79 |
| 43| 14281 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10078 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 747 | 42.46 | 12.20 | 0.61 |
| 4 | 227 | 858 | 47.48 | 13.79 | 0.67 |
| 5 | 282 | 969 | 59.63 | 17.18 | 0.80 |
| 6 | 338 | 1081 | 67.85 | 19.52 | 0.89 |
| 7 | 393 | 1192 | 81.46 | 23.31 | 1.03 |
| 8 | 450 | 1303 | 85.60 | 24.57 | 1.08 |
| 9 | 506 | 1414 | 92.25 | 26.62 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1812 | 24.00 | 7.62 | 0.48 |
| 2| 1967 | 26.79 | 9.05 | 0.52 |
| 3| 2099 | 27.97 | 10.06 | 0.54 |
| 5| 2440 | 32.36 | 12.61 | 0.61 |
| 10| 3091 | 39.69 | 18.00 | 0.74 |
| 40| 7534 | 96.76 | 53.83 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 638 | 22.80 | 7.38 | 0.42 |
| 2| 699 | 22.55 | 7.94 | 0.42 |
| 3| 919 | 26.67 | 9.78 | 0.48 |
| 5| 1115 | 27.09 | 11.21 | 0.50 |
| 10| 1905 | 38.73 | 17.80 | 0.68 |
| 38| 6238 | 93.99 | 51.83 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 27.47 | 8.46 | 0.46 |
| 2| 794 | 30.91 | 10.06 | 0.51 |
| 3| 990 | 33.47 | 11.45 | 0.55 |
| 5| 1308 | 34.93 | 13.22 | 0.59 |
| 10| 1946 | 43.44 | 18.93 | 0.72 |
| 37| 6121 | 99.75 | 52.78 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 33.83 | 10.16 | 0.53 |
| 2| 806 | 35.81 | 11.37 | 0.56 |
| 3| 1000 | 38.51 | 12.80 | 0.60 |
| 5| 1244 | 42.72 | 15.30 | 0.66 |
| 10| 2074 | 54.88 | 22.05 | 0.84 |
| 29| 4841 | 96.76 | 46.32 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5783 | 27.04 | 9.08 | 0.69 |
| 2| 6050 | 36.80 | 12.43 | 0.80 |
| 3| 6041 | 43.72 | 14.64 | 0.87 |
| 4| 6283 | 52.19 | 17.61 | 0.98 |
| 5| 6390 | 60.80 | 20.45 | 1.07 |
| 6| 6457 | 69.64 | 23.42 | 1.17 |
| 7| 6738 | 84.55 | 28.53 | 1.34 |
| 8| 6848 | 92.49 | 31.18 | 1.42 |
| 9| 7065 | 98.32 | 33.16 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 20 | 1139 | 6513 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1704 | 6850 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2217 | 7156 | 98.93 | 37.88 | 1.54 |

