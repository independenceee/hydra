--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-09-29 04:14:40.506882235 UTC |
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
| 1| 5841 | 10.19 | 3.22 | 0.51 |
| 2| 6039 | 12.25 | 3.87 | 0.54 |
| 3| 6236 | 14.69 | 4.65 | 0.58 |
| 5| 6641 | 19.00 | 6.01 | 0.64 |
| 10| 7646 | 29.00 | 9.14 | 0.79 |
| 43| 14281 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 169 | 747 | 43.67 | 12.53 | 0.63 |
| 4 | 225 | 858 | 50.96 | 14.62 | 0.71 |
| 5 | 281 | 969 | 57.39 | 16.55 | 0.78 |
| 6 | 339 | 1081 | 70.37 | 20.16 | 0.91 |
| 7 | 394 | 1192 | 76.20 | 21.87 | 0.98 |
| 8 | 451 | 1303 | 96.42 | 27.21 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1826 | 24.00 | 7.62 | 0.48 |
| 2| 1879 | 24.77 | 8.48 | 0.49 |
| 3| 2058 | 27.39 | 9.88 | 0.53 |
| 5| 2391 | 30.96 | 12.23 | 0.59 |
| 10| 3034 | 38.43 | 17.65 | 0.72 |
| 41| 7591 | 96.97 | 54.54 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 654 | 22.81 | 7.37 | 0.42 |
| 2| 751 | 24.35 | 8.48 | 0.44 |
| 3| 948 | 26.20 | 9.64 | 0.47 |
| 5| 1263 | 30.19 | 12.08 | 0.54 |
| 10| 2111 | 40.81 | 18.38 | 0.71 |
| 40| 6432 | 95.61 | 53.62 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 29.17 | 8.91 | 0.48 |
| 2| 740 | 30.27 | 9.86 | 0.50 |
| 3| 1034 | 31.61 | 10.96 | 0.53 |
| 5| 1281 | 35.12 | 13.27 | 0.59 |
| 10| 2106 | 45.76 | 19.62 | 0.75 |
| 37| 6216 | 99.90 | 52.82 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.15 | 0.53 |
| 2| 773 | 35.14 | 11.16 | 0.55 |
| 3| 1012 | 38.58 | 12.82 | 0.60 |
| 5| 1276 | 42.49 | 15.24 | 0.66 |
| 10| 2102 | 55.06 | 22.12 | 0.85 |
| 28| 4961 | 98.59 | 46.25 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5791 | 27.00 | 9.07 | 0.69 |
| 2| 5959 | 35.96 | 12.09 | 0.79 |
| 3| 6045 | 41.63 | 13.93 | 0.85 |
| 4| 6177 | 52.68 | 17.66 | 0.97 |
| 5| 6502 | 65.29 | 22.12 | 1.12 |
| 6| 6640 | 71.89 | 24.26 | 1.20 |
| 7| 6726 | 83.33 | 28.04 | 1.32 |
| 8| 6701 | 85.02 | 28.49 | 1.34 |
| 9| 6958 | 98.95 | 33.19 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6512 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1705 | 6851 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2221 | 7160 | 98.68 | 37.80 | 1.54 |

