--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-17 04:36:53.416724144 UTC |
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
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 14.90 | 4.72 | 0.58 |
| 5| 6641 | 18.72 | 5.91 | 0.64 |
| 10| 7647 | 29.11 | 9.17 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10079 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 112 | 635 | 32.34 | 9.42 | 0.51 |
| 3 | 171 | 751 | 41.19 | 11.92 | 0.60 |
| 4 | 227 | 862 | 53.97 | 15.37 | 0.74 |
| 5 | 281 | 969 | 62.72 | 17.92 | 0.83 |
| 6 | 340 | 1081 | 66.15 | 19.07 | 0.87 |
| 7 | 393 | 1192 | 85.29 | 24.14 | 1.07 |
| 8 | 449 | 1303 | 90.35 | 25.80 | 1.12 |
| 10 | 560 | 1525 | 97.19 | 28.20 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 23.92 | 7.60 | 0.48 |
| 2| 1999 | 26.50 | 8.99 | 0.52 |
| 3| 2147 | 29.58 | 10.49 | 0.56 |
| 5| 2317 | 30.04 | 11.97 | 0.58 |
| 10| 3062 | 39.44 | 17.93 | 0.73 |
| 41| 7516 | 96.18 | 54.33 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 699 | 22.62 | 7.96 | 0.42 |
| 3| 898 | 25.83 | 9.54 | 0.47 |
| 5| 1244 | 30.85 | 12.30 | 0.54 |
| 10| 2073 | 42.34 | 18.80 | 0.72 |
| 41| 6487 | 96.12 | 54.44 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.17 | 8.91 | 0.48 |
| 2| 856 | 31.62 | 10.27 | 0.52 |
| 3| 954 | 33.51 | 11.46 | 0.55 |
| 5| 1288 | 37.81 | 14.01 | 0.61 |
| 10| 2152 | 46.14 | 19.75 | 0.76 |
| 36| 5975 | 97.53 | 51.47 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.87 | 10.16 | 0.53 |
| 2| 807 | 35.89 | 11.39 | 0.56 |
| 3| 942 | 37.87 | 12.61 | 0.59 |
| 5| 1349 | 44.03 | 15.70 | 0.68 |
| 10| 2075 | 54.96 | 22.07 | 0.84 |
| 29| 4790 | 98.02 | 46.68 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5781 | 27.04 | 9.09 | 0.69 |
| 2| 5846 | 31.55 | 10.51 | 0.74 |
| 3| 6157 | 45.97 | 15.50 | 0.90 |
| 4| 6231 | 54.95 | 18.52 | 1.00 |
| 5| 6582 | 65.85 | 22.35 | 1.13 |
| 6| 6479 | 67.07 | 22.52 | 1.14 |
| 7| 6805 | 85.16 | 28.76 | 1.35 |
| 8| 6950 | 91.35 | 30.88 | 1.42 |
| 9| 6810 | 95.14 | 31.92 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 20 | 1139 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1708 | 6854 | 80.67 | 30.67 | 1.32 |
| 10 | 38 | 2162 | 7124 | 97.07 | 37.14 | 1.52 |

