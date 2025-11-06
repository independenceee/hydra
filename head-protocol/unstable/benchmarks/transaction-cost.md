--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-06 04:36:25.867028482 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 13.08 | 4.16 | 0.55 |
| 3| 6242 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 99.11 | 30.98 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10042 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 169 | 751 | 43.48 | 12.44 | 0.62 |
| 4 | 228 | 858 | 48.08 | 13.96 | 0.68 |
| 5 | 284 | 969 | 64.14 | 18.19 | 0.84 |
| 6 | 338 | 1081 | 67.64 | 19.46 | 0.88 |
| 7 | 395 | 1196 | 82.97 | 23.58 | 1.04 |
| 8 | 449 | 1303 | 98.37 | 27.57 | 1.20 |
| 9 | 506 | 1418 | 92.39 | 26.82 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.37 | 7.71 | 0.48 |
| 2| 1949 | 25.51 | 8.70 | 0.50 |
| 3| 2110 | 28.10 | 10.10 | 0.54 |
| 5| 2391 | 30.96 | 12.23 | 0.59 |
| 10| 3070 | 39.94 | 18.05 | 0.74 |
| 40| 7675 | 98.74 | 54.44 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.81 | 7.37 | 0.42 |
| 2| 722 | 22.52 | 7.93 | 0.42 |
| 3| 954 | 26.61 | 9.77 | 0.48 |
| 5| 1135 | 28.15 | 11.51 | 0.51 |
| 10| 1939 | 38.55 | 17.78 | 0.68 |
| 40| 6514 | 96.18 | 53.78 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.17 | 8.91 | 0.48 |
| 2| 782 | 30.98 | 10.08 | 0.51 |
| 3| 1036 | 31.61 | 10.96 | 0.53 |
| 5| 1219 | 34.26 | 13.02 | 0.57 |
| 10| 1929 | 46.54 | 19.78 | 0.75 |
| 36| 5912 | 95.74 | 50.96 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 984 | 38.58 | 12.82 | 0.60 |
| 5| 1291 | 43.16 | 15.45 | 0.67 |
| 10| 2149 | 55.18 | 22.16 | 0.85 |
| 28| 4666 | 95.08 | 45.20 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5809 | 27.09 | 9.09 | 0.69 |
| 2| 5938 | 35.76 | 12.03 | 0.79 |
| 3| 6116 | 45.62 | 15.37 | 0.90 |
| 4| 6242 | 51.36 | 17.25 | 0.96 |
| 5| 6486 | 65.14 | 21.97 | 1.12 |
| 6| 6694 | 76.70 | 25.91 | 1.25 |
| 7| 6767 | 82.62 | 27.87 | 1.32 |
| 8| 6683 | 84.38 | 28.23 | 1.33 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 286 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 40.58 | 14.82 | 0.86 |
| 10 | 30 | 1709 | 6855 | 80.92 | 30.76 | 1.33 |
| 10 | 36 | 2047 | 7055 | 91.90 | 35.16 | 1.46 |

