--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-14 04:47:34.84743371 UTC |
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
| 1| 5838 | 10.47 | 3.32 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.47 | 9.30 | 0.79 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 735 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10041 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 112 | 635 | 32.19 | 9.36 | 0.51 |
| 3 | 169 | 747 | 43.48 | 12.44 | 0.62 |
| 4 | 227 | 858 | 48.35 | 14.05 | 0.68 |
| 5 | 280 | 969 | 64.64 | 18.32 | 0.85 |
| 6 | 338 | 1085 | 63.85 | 18.55 | 0.85 |
| 7 | 394 | 1192 | 80.77 | 23.01 | 1.02 |
| 8 | 449 | 1307 | 98.26 | 27.50 | 1.20 |
| 9 | 504 | 1414 | 98.16 | 27.91 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.37 | 7.71 | 0.48 |
| 2| 1976 | 26.96 | 9.10 | 0.52 |
| 3| 2054 | 27.47 | 9.90 | 0.53 |
| 5| 2347 | 30.30 | 12.03 | 0.59 |
| 10| 3050 | 39.81 | 18.02 | 0.74 |
| 43| 7799 | 98.70 | 56.41 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.57 | 7.32 | 0.41 |
| 2| 754 | 24.01 | 8.38 | 0.44 |
| 3| 898 | 25.82 | 9.54 | 0.47 |
| 5| 1178 | 28.77 | 11.71 | 0.52 |
| 10| 1931 | 38.46 | 17.74 | 0.67 |
| 41| 6689 | 97.60 | 54.87 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 27.50 | 8.46 | 0.46 |
| 2| 778 | 30.98 | 10.08 | 0.51 |
| 3| 947 | 30.82 | 10.73 | 0.52 |
| 5| 1352 | 36.43 | 13.67 | 0.60 |
| 10| 2091 | 45.77 | 19.62 | 0.75 |
| 35| 6091 | 99.24 | 51.39 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.15 | 0.53 |
| 2| 818 | 36.18 | 11.48 | 0.56 |
| 3| 1012 | 38.55 | 12.81 | 0.60 |
| 5| 1360 | 43.17 | 15.45 | 0.67 |
| 10| 2007 | 53.91 | 21.77 | 0.83 |
| 30| 4958 | 99.89 | 47.86 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5790 | 27.16 | 9.11 | 0.69 |
| 2| 5907 | 32.49 | 10.85 | 0.75 |
| 3| 6100 | 42.42 | 14.24 | 0.86 |
| 4| 6139 | 50.74 | 17.00 | 0.95 |
| 5| 6424 | 65.35 | 22.01 | 1.12 |
| 6| 6549 | 71.82 | 24.21 | 1.19 |
| 7| 6763 | 84.12 | 28.41 | 1.33 |
| 8| 6861 | 89.43 | 30.10 | 1.39 |
| 9| 6959 | 96.64 | 32.48 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 20.52 | 6.86 | 0.62 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 283 | 6003 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 567 | 6171 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1710 | 6856 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2165 | 7127 | 97.33 | 37.23 | 1.52 |

