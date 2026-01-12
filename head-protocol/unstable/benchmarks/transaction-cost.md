--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-12 05:00:59.559576532 UTC |
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
| 1| 5837 | 10.40 | 3.30 | 0.51 |
| 2| 6038 | 12.53 | 3.97 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.50 | 5.83 | 0.63 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 563 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 39.97 | 11.62 | 0.59 |
| 4 | 227 | 858 | 53.17 | 15.15 | 0.73 |
| 5 | 284 | 969 | 59.27 | 17.06 | 0.79 |
| 6 | 337 | 1081 | 66.16 | 19.07 | 0.87 |
| 7 | 393 | 1192 | 80.48 | 22.90 | 1.02 |
| 8 | 448 | 1303 | 92.20 | 26.20 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1807 | 23.92 | 7.60 | 0.48 |
| 2| 1923 | 25.47 | 8.70 | 0.50 |
| 3| 2091 | 27.32 | 9.86 | 0.53 |
| 5| 2453 | 32.68 | 12.69 | 0.61 |
| 10| 3019 | 38.78 | 17.73 | 0.72 |
| 41| 7652 | 97.07 | 54.62 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 618 | 22.57 | 7.31 | 0.41 |
| 2| 775 | 23.56 | 8.22 | 0.43 |
| 3| 1010 | 28.33 | 10.23 | 0.50 |
| 5| 1133 | 28.18 | 11.51 | 0.51 |
| 10| 1968 | 39.11 | 17.94 | 0.68 |
| 41| 6703 | 99.41 | 55.41 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 602 | 28.46 | 8.69 | 0.47 |
| 2| 800 | 29.22 | 9.61 | 0.49 |
| 3| 990 | 31.16 | 10.83 | 0.52 |
| 5| 1282 | 37.77 | 14.00 | 0.61 |
| 10| 2096 | 48.48 | 20.37 | 0.78 |
| 35| 5821 | 99.61 | 51.35 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 668 | 33.87 | 10.16 | 0.53 |
| 2| 764 | 35.14 | 11.16 | 0.55 |
| 3| 938 | 37.95 | 12.63 | 0.59 |
| 5| 1344 | 43.13 | 15.44 | 0.67 |
| 10| 2007 | 53.16 | 21.54 | 0.82 |
| 30| 5028 | 99.91 | 47.90 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.58 | 0.64 |
| 2| 6016 | 37.05 | 12.49 | 0.80 |
| 3| 6084 | 45.02 | 15.11 | 0.89 |
| 4| 6186 | 51.31 | 17.21 | 0.96 |
| 5| 6355 | 60.58 | 20.37 | 1.07 |
| 6| 6610 | 71.96 | 24.20 | 1.20 |
| 7| 6722 | 83.55 | 28.13 | 1.32 |
| 8| 6926 | 93.69 | 31.68 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.79 | 10.58 | 0.73 |
| 10 | 20 | 1138 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2218 | 7157 | 99.56 | 38.10 | 1.54 |

