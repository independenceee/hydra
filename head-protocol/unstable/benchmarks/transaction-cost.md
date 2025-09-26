--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-09-26 04:15:37.895124979 UTC |
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
| 1| 5834 | 10.47 | 3.32 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 19.17 | 6.07 | 0.64 |
| 10| 7644 | 29.11 | 9.17 | 0.79 |
| 43| 14282 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1275 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10045 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 171 | 747 | 41.12 | 11.90 | 0.60 |
| 4 | 228 | 858 | 50.68 | 14.55 | 0.70 |
| 5 | 282 | 974 | 59.03 | 16.94 | 0.79 |
| 6 | 338 | 1081 | 75.54 | 21.36 | 0.96 |
| 7 | 394 | 1192 | 74.52 | 21.47 | 0.96 |
| 8 | 451 | 1303 | 89.27 | 25.39 | 1.11 |
| 9 | 505 | 1414 | 91.85 | 26.57 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 23.92 | 7.60 | 0.48 |
| 2| 1987 | 26.47 | 8.98 | 0.52 |
| 3| 2017 | 26.36 | 9.59 | 0.52 |
| 5| 2387 | 31.49 | 12.36 | 0.60 |
| 10| 3237 | 41.69 | 18.58 | 0.76 |
| 42| 7608 | 96.64 | 55.16 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 638 | 22.57 | 7.32 | 0.41 |
| 2| 818 | 25.16 | 8.70 | 0.45 |
| 3| 946 | 26.63 | 9.78 | 0.48 |
| 5| 1306 | 31.09 | 12.34 | 0.55 |
| 10| 2022 | 39.27 | 17.98 | 0.69 |
| 41| 6662 | 97.92 | 54.94 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 27.54 | 8.47 | 0.46 |
| 2| 740 | 30.27 | 9.86 | 0.50 |
| 3| 957 | 33.47 | 11.46 | 0.55 |
| 5| 1362 | 36.35 | 13.65 | 0.60 |
| 10| 1887 | 46.43 | 19.73 | 0.75 |
| 37| 5993 | 98.81 | 52.49 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 708 | 33.87 | 10.16 | 0.53 |
| 2| 806 | 35.85 | 11.38 | 0.56 |
| 3| 900 | 37.24 | 12.41 | 0.58 |
| 5| 1302 | 43.36 | 15.49 | 0.67 |
| 10| 2098 | 54.65 | 21.99 | 0.84 |
| 30| 4787 | 97.72 | 47.19 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.08 | 9.08 | 0.69 |
| 2| 6021 | 36.89 | 12.44 | 0.80 |
| 3| 5995 | 41.48 | 13.88 | 0.85 |
| 4| 6080 | 46.81 | 15.60 | 0.91 |
| 5| 6440 | 63.37 | 21.37 | 1.10 |
| 6| 6769 | 75.66 | 25.70 | 1.24 |
| 7| 6884 | 85.40 | 28.85 | 1.35 |
| 8| 6947 | 90.87 | 30.64 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1710 | 6856 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2164 | 7126 | 96.88 | 37.08 | 1.51 |

