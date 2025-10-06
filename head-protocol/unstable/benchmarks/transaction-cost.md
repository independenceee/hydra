--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-06 04:16:39.805300762 UTC |
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
| 1| 5834 | 10.40 | 3.30 | 0.51 |
| 2| 6038 | 12.91 | 4.10 | 0.55 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 33.25 | 9.63 | 0.52 |
| 3 | 170 | 747 | 42.45 | 12.22 | 0.61 |
| 4 | 227 | 862 | 52.42 | 15.00 | 0.72 |
| 5 | 283 | 969 | 55.63 | 16.16 | 0.76 |
| 6 | 339 | 1081 | 75.26 | 21.25 | 0.96 |
| 7 | 394 | 1192 | 79.55 | 22.85 | 1.01 |
| 8 | 450 | 1303 | 82.06 | 23.66 | 1.04 |
| 10 | 561 | 1525 | 97.25 | 28.10 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.29 | 7.69 | 0.48 |
| 2| 1932 | 25.47 | 8.69 | 0.50 |
| 3| 2060 | 27.02 | 9.79 | 0.53 |
| 5| 2508 | 33.12 | 12.83 | 0.62 |
| 10| 3246 | 41.69 | 18.57 | 0.76 |
| 41| 7701 | 99.60 | 55.29 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 22.84 | 7.37 | 0.42 |
| 2| 766 | 24.01 | 8.38 | 0.44 |
| 3| 831 | 24.13 | 9.05 | 0.45 |
| 5| 1327 | 32.60 | 12.75 | 0.56 |
| 10| 1966 | 38.38 | 17.71 | 0.67 |
| 45| 6981 | 99.67 | 58.09 | 1.68 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.54 | 8.47 | 0.46 |
| 2| 784 | 30.95 | 10.07 | 0.51 |
| 3| 934 | 32.79 | 11.25 | 0.54 |
| 5| 1196 | 36.31 | 13.56 | 0.59 |
| 10| 2106 | 45.42 | 19.54 | 0.75 |
| 35| 5933 | 96.86 | 50.66 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 33.83 | 10.15 | 0.53 |
| 2| 768 | 35.21 | 11.18 | 0.55 |
| 3| 1003 | 38.55 | 12.81 | 0.60 |
| 5| 1260 | 42.57 | 15.26 | 0.66 |
| 10| 2010 | 54.21 | 21.85 | 0.83 |
| 28| 4837 | 96.49 | 45.65 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.05 | 9.07 | 0.69 |
| 2| 5985 | 36.80 | 12.42 | 0.80 |
| 3| 6125 | 46.01 | 15.51 | 0.90 |
| 4| 6237 | 54.00 | 18.14 | 0.99 |
| 5| 6415 | 63.62 | 21.45 | 1.10 |
| 6| 6411 | 68.40 | 22.93 | 1.15 |
| 7| 6823 | 85.84 | 28.96 | 1.35 |
| 8| 6942 | 93.50 | 31.52 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 20.52 | 6.98 | 0.62 |
| 10 | 20 | 1139 | 6514 | 60.87 | 22.83 | 1.09 |
| 10 | 39 | 2223 | 7162 | 97.61 | 37.43 | 1.52 |

