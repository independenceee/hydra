--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-08 04:14:33.74970504 UTC |
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
| 1| 5838 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.70 | 4.03 | 0.55 |
| 3| 6239 | 15.07 | 4.78 | 0.58 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7647 | 29.18 | 9.20 | 0.79 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.40 | 9.67 | 0.52 |
| 3 | 170 | 747 | 41.42 | 12.01 | 0.60 |
| 4 | 225 | 858 | 47.52 | 13.80 | 0.67 |
| 5 | 282 | 969 | 57.44 | 16.56 | 0.78 |
| 6 | 338 | 1081 | 71.04 | 20.20 | 0.92 |
| 7 | 395 | 1192 | 80.56 | 22.92 | 1.02 |
| 8 | 451 | 1303 | 92.20 | 26.20 | 1.14 |
| 9 | 504 | 1418 | 96.76 | 27.70 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1792 | 24.00 | 7.62 | 0.48 |
| 2| 1947 | 25.84 | 8.78 | 0.51 |
| 3| 2125 | 28.09 | 10.09 | 0.54 |
| 5| 2361 | 31.45 | 12.35 | 0.60 |
| 10| 3283 | 42.85 | 18.88 | 0.78 |
| 43| 7858 | 98.89 | 56.44 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.54 | 7.30 | 0.41 |
| 2| 809 | 25.07 | 8.68 | 0.45 |
| 3| 828 | 24.06 | 9.02 | 0.45 |
| 5| 1197 | 28.04 | 11.48 | 0.51 |
| 10| 1984 | 39.61 | 18.05 | 0.69 |
| 38| 6374 | 96.47 | 52.52 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 655 | 29.17 | 8.91 | 0.48 |
| 2| 768 | 30.87 | 10.05 | 0.51 |
| 3| 873 | 32.09 | 11.03 | 0.53 |
| 5| 1261 | 37.81 | 14.01 | 0.61 |
| 10| 2080 | 45.77 | 19.62 | 0.75 |
| 35| 5874 | 96.18 | 50.42 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 764 | 35.14 | 11.16 | 0.55 |
| 3| 945 | 37.95 | 12.63 | 0.59 |
| 5| 1368 | 44.07 | 15.71 | 0.68 |
| 10| 1978 | 53.35 | 21.59 | 0.82 |
| 28| 4916 | 98.87 | 46.34 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5810 | 27.00 | 9.06 | 0.69 |
| 2| 5950 | 35.92 | 12.07 | 0.79 |
| 3| 5954 | 40.69 | 13.59 | 0.84 |
| 4| 6254 | 51.90 | 17.53 | 0.97 |
| 5| 6325 | 60.43 | 20.26 | 1.06 |
| 6| 6630 | 71.21 | 24.02 | 1.19 |
| 7| 6688 | 79.21 | 26.67 | 1.28 |
| 8| 6979 | 95.23 | 32.15 | 1.46 |
| 9| 6981 | 96.94 | 32.62 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.93 | 6.32 | 0.61 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6174 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1704 | 6851 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2220 | 7159 | 98.05 | 37.58 | 1.53 |

