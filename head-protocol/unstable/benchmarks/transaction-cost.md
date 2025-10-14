--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-14 04:15:18.471367226 UTC |
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
| 1| 5840 | 10.78 | 3.43 | 0.52 |
| 2| 6035 | 12.73 | 4.04 | 0.55 |
| 3| 6239 | 14.97 | 4.75 | 0.58 |
| 5| 6640 | 19.00 | 6.01 | 0.64 |
| 10| 7647 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 43.77 | 12.52 | 0.63 |
| 4 | 227 | 858 | 48.05 | 13.98 | 0.68 |
| 5 | 281 | 969 | 64.34 | 18.28 | 0.84 |
| 6 | 341 | 1081 | 75.46 | 21.41 | 0.96 |
| 7 | 395 | 1192 | 86.68 | 24.42 | 1.08 |
| 8 | 449 | 1303 | 94.76 | 26.86 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1809 | 24.29 | 7.69 | 0.48 |
| 2| 1951 | 25.76 | 8.76 | 0.51 |
| 3| 2190 | 29.01 | 10.35 | 0.56 |
| 5| 2497 | 32.21 | 12.57 | 0.61 |
| 10| 3245 | 42.46 | 18.76 | 0.77 |
| 40| 7608 | 99.44 | 54.58 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.81 | 7.37 | 0.42 |
| 2| 771 | 24.35 | 8.48 | 0.44 |
| 3| 913 | 25.14 | 9.33 | 0.46 |
| 5| 1227 | 30.81 | 12.28 | 0.54 |
| 10| 2011 | 40.23 | 18.26 | 0.70 |
| 42| 6780 | 99.93 | 56.13 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 27.54 | 8.47 | 0.46 |
| 2| 733 | 30.27 | 9.86 | 0.50 |
| 3| 949 | 30.94 | 10.75 | 0.52 |
| 5| 1249 | 37.06 | 13.78 | 0.60 |
| 10| 2041 | 44.63 | 19.30 | 0.74 |
| 36| 5690 | 98.67 | 51.66 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 703 | 33.83 | 10.15 | 0.53 |
| 2| 872 | 36.60 | 11.61 | 0.57 |
| 3| 1027 | 38.63 | 12.83 | 0.60 |
| 5| 1225 | 41.93 | 15.06 | 0.65 |
| 10| 2036 | 54.17 | 21.84 | 0.83 |
| 28| 4989 | 99.23 | 46.47 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5807 | 26.97 | 9.06 | 0.69 |
| 2| 6004 | 37.08 | 12.49 | 0.80 |
| 3| 6153 | 45.60 | 15.37 | 0.90 |
| 4| 6178 | 52.93 | 17.78 | 0.98 |
| 5| 6504 | 65.04 | 21.98 | 1.12 |
| 6| 6686 | 74.43 | 25.18 | 1.23 |
| 7| 6696 | 83.34 | 28.08 | 1.32 |
| 8| 6942 | 91.00 | 30.79 | 1.41 |
| 9| 7026 | 99.93 | 33.72 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.71 | 7.04 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1137 | 6512 | 60.87 | 22.83 | 1.09 |
| 10 | 40 | 2275 | 7191 | 99.40 | 38.15 | 1.54 |
| 10 | 36 | 2052 | 7060 | 94.11 | 35.91 | 1.48 |

