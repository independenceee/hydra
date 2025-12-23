--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-23 04:48:25.804685223 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6035 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6643 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14285 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10044 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 170 | 747 | 43.66 | 12.53 | 0.63 |
| 4 | 227 | 858 | 48.18 | 13.98 | 0.68 |
| 5 | 283 | 969 | 55.97 | 16.24 | 0.76 |
| 6 | 340 | 1081 | 70.72 | 20.32 | 0.92 |
| 7 | 393 | 1192 | 80.60 | 22.97 | 1.02 |
| 8 | 452 | 1307 | 96.72 | 27.38 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1817 | 24.00 | 7.62 | 0.48 |
| 2| 1926 | 25.88 | 8.79 | 0.51 |
| 3| 2062 | 27.02 | 9.79 | 0.53 |
| 5| 2350 | 30.34 | 12.04 | 0.59 |
| 10| 3081 | 39.63 | 17.98 | 0.74 |
| 41| 7610 | 96.74 | 54.54 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 613 | 22.80 | 7.38 | 0.41 |
| 2| 764 | 23.59 | 8.23 | 0.43 |
| 3| 917 | 25.07 | 9.31 | 0.46 |
| 5| 1095 | 27.04 | 11.19 | 0.50 |
| 10| 2052 | 42.28 | 18.80 | 0.72 |
| 40| 6319 | 92.43 | 52.75 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.13 | 8.90 | 0.48 |
| 2| 770 | 28.51 | 9.39 | 0.48 |
| 3| 910 | 32.72 | 11.23 | 0.54 |
| 5| 1168 | 33.51 | 12.79 | 0.56 |
| 10| 2028 | 47.97 | 20.21 | 0.77 |
| 37| 6098 | 99.15 | 52.59 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.79 | 10.15 | 0.53 |
| 2| 819 | 35.89 | 11.39 | 0.56 |
| 3| 895 | 37.24 | 12.41 | 0.58 |
| 5| 1261 | 42.64 | 15.28 | 0.66 |
| 10| 2065 | 54.77 | 22.02 | 0.84 |
| 28| 4647 | 94.61 | 45.07 | 1.44 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.08 | 9.08 | 0.69 |
| 2| 5919 | 36.07 | 12.12 | 0.79 |
| 3| 6066 | 45.00 | 15.13 | 0.89 |
| 4| 6232 | 54.88 | 18.50 | 1.00 |
| 5| 6479 | 64.23 | 21.74 | 1.11 |
| 6| 6629 | 73.62 | 24.88 | 1.22 |
| 7| 6839 | 84.08 | 28.41 | 1.34 |
| 8| 6848 | 93.38 | 31.54 | 1.43 |
| 9| 6872 | 95.11 | 32.01 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.49 | 6.17 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6175 | 40.83 | 14.90 | 0.86 |
| 10 | 20 | 1140 | 6514 | 58.84 | 22.14 | 1.07 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2220 | 7160 | 98.49 | 37.73 | 1.53 |

