--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-09-27 04:13:48.272504147 UTC |
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
| 2| 6037 | 12.99 | 4.13 | 0.55 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.02 | 9.14 | 0.79 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 563 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10077 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 170 | 747 | 41.34 | 11.94 | 0.60 |
| 4 | 228 | 858 | 52.50 | 15.02 | 0.72 |
| 5 | 283 | 969 | 56.11 | 16.27 | 0.76 |
| 6 | 337 | 1081 | 68.00 | 19.52 | 0.89 |
| 7 | 397 | 1192 | 80.70 | 23.08 | 1.02 |
| 8 | 449 | 1303 | 96.33 | 27.19 | 1.18 |
| 9 | 504 | 1414 | 89.24 | 25.89 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1887 | 24.77 | 8.48 | 0.49 |
| 3| 2085 | 27.35 | 9.87 | 0.53 |
| 5| 2388 | 31.45 | 12.35 | 0.60 |
| 10| 3141 | 40.75 | 18.29 | 0.75 |
| 41| 7853 | 99.01 | 55.19 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 641 | 22.81 | 7.37 | 0.42 |
| 2| 847 | 25.37 | 8.75 | 0.46 |
| 3| 899 | 25.10 | 9.32 | 0.46 |
| 5| 1255 | 31.21 | 12.38 | 0.55 |
| 10| 2039 | 39.72 | 18.07 | 0.69 |
| 41| 6663 | 98.52 | 55.12 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 29.17 | 8.91 | 0.48 |
| 2| 770 | 28.55 | 9.40 | 0.48 |
| 3| 872 | 32.09 | 11.03 | 0.53 |
| 5| 1253 | 34.90 | 13.21 | 0.58 |
| 10| 2018 | 44.25 | 19.18 | 0.73 |
| 36| 5959 | 98.34 | 51.69 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 33.83 | 10.15 | 0.53 |
| 2| 838 | 35.92 | 11.40 | 0.56 |
| 3| 984 | 38.58 | 12.82 | 0.60 |
| 5| 1203 | 41.86 | 15.04 | 0.65 |
| 10| 2079 | 54.81 | 22.03 | 0.84 |
| 29| 5022 | 99.39 | 47.09 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5783 | 27.16 | 9.10 | 0.69 |
| 2| 5953 | 35.93 | 12.07 | 0.79 |
| 3| 6026 | 41.37 | 13.84 | 0.85 |
| 4| 6335 | 55.32 | 18.72 | 1.01 |
| 5| 6393 | 64.19 | 21.60 | 1.11 |
| 6| 6649 | 73.72 | 24.88 | 1.22 |
| 7| 6751 | 84.46 | 28.46 | 1.33 |
| 8| 6895 | 92.13 | 30.99 | 1.42 |
| 9| 7087 | 96.70 | 32.63 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1136 | 6510 | 58.66 | 22.07 | 1.07 |
| 10 | 40 | 2274 | 7190 | 99.66 | 38.24 | 1.55 |

