--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-10 04:43:24.635715634 UTC |
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
| 1| 5836 | 10.36 | 3.28 | 0.51 |
| 2| 6035 | 13.01 | 4.14 | 0.55 |
| 3| 6242 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.81 | 5.94 | 0.64 |
| 10| 7650 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1273 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10042 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 169 | 747 | 42.38 | 12.20 | 0.61 |
| 4 | 227 | 858 | 48.22 | 13.99 | 0.68 |
| 5 | 282 | 969 | 58.00 | 16.70 | 0.78 |
| 6 | 337 | 1085 | 73.80 | 20.94 | 0.95 |
| 7 | 394 | 1192 | 74.17 | 21.47 | 0.96 |
| 8 | 450 | 1303 | 87.52 | 25.08 | 1.10 |
| 9 | 505 | 1418 | 96.61 | 27.66 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 24.37 | 7.71 | 0.48 |
| 2| 1996 | 26.47 | 8.98 | 0.52 |
| 3| 2142 | 28.13 | 10.10 | 0.54 |
| 5| 2368 | 30.27 | 12.04 | 0.59 |
| 10| 3249 | 42.21 | 18.70 | 0.77 |
| 40| 7651 | 98.00 | 54.20 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 617 | 22.84 | 7.37 | 0.42 |
| 2| 850 | 25.37 | 8.76 | 0.46 |
| 3| 857 | 24.11 | 9.04 | 0.45 |
| 5| 1217 | 29.04 | 11.76 | 0.52 |
| 10| 2024 | 40.67 | 18.35 | 0.70 |
| 40| 6359 | 94.40 | 53.32 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 29.13 | 8.90 | 0.48 |
| 2| 800 | 30.87 | 10.05 | 0.51 |
| 3| 914 | 32.79 | 11.25 | 0.54 |
| 5| 1184 | 36.24 | 13.54 | 0.59 |
| 10| 2038 | 48.16 | 20.26 | 0.78 |
| 36| 5933 | 98.47 | 51.73 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.17 | 11.17 | 0.55 |
| 3| 899 | 37.13 | 12.38 | 0.58 |
| 5| 1331 | 43.43 | 15.51 | 0.67 |
| 10| 2040 | 54.25 | 21.85 | 0.84 |
| 29| 5008 | 98.86 | 47.00 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5794 | 27.09 | 9.10 | 0.69 |
| 2| 5870 | 34.84 | 11.67 | 0.77 |
| 3| 5945 | 40.40 | 13.47 | 0.84 |
| 4| 6208 | 53.97 | 18.12 | 0.99 |
| 5| 6172 | 52.29 | 17.38 | 0.97 |
| 6| 6541 | 70.56 | 23.78 | 1.18 |
| 7| 6696 | 83.50 | 28.18 | 1.32 |
| 8| 6959 | 93.58 | 31.63 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6512 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1705 | 6851 | 81.37 | 30.91 | 1.33 |
| 10 | 40 | 2275 | 7191 | 99.22 | 38.09 | 1.54 |
| 10 | 35 | 1993 | 7024 | 91.17 | 34.80 | 1.45 |

