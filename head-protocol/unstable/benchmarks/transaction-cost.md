--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-27 04:32:52.509466574 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6035 | 12.99 | 4.13 | 0.55 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 29.11 | 9.17 | 0.79 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 40.00 | 11.63 | 0.59 |
| 4 | 226 | 858 | 53.53 | 15.26 | 0.73 |
| 5 | 282 | 969 | 62.49 | 17.80 | 0.83 |
| 6 | 339 | 1085 | 73.10 | 20.74 | 0.94 |
| 7 | 394 | 1192 | 78.16 | 22.30 | 0.99 |
| 8 | 448 | 1303 | 94.61 | 26.78 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 24.29 | 7.69 | 0.48 |
| 2| 1944 | 25.55 | 8.71 | 0.51 |
| 3| 2053 | 27.03 | 9.79 | 0.53 |
| 5| 2524 | 34.14 | 13.12 | 0.63 |
| 10| 3266 | 42.70 | 18.84 | 0.77 |
| 39| 7468 | 96.99 | 53.24 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 625 | 22.81 | 7.37 | 0.42 |
| 2| 769 | 23.59 | 8.23 | 0.43 |
| 3| 967 | 26.71 | 9.81 | 0.48 |
| 5| 1132 | 28.11 | 11.49 | 0.51 |
| 10| 2047 | 42.35 | 18.84 | 0.72 |
| 41| 6597 | 99.86 | 55.48 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.46 | 8.69 | 0.47 |
| 2| 770 | 30.91 | 10.06 | 0.51 |
| 3| 1013 | 31.65 | 10.97 | 0.53 |
| 5| 1266 | 34.94 | 13.22 | 0.58 |
| 10| 2052 | 44.93 | 19.38 | 0.74 |
| 35| 5922 | 96.05 | 50.44 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 33.83 | 10.15 | 0.53 |
| 2| 808 | 35.85 | 11.38 | 0.56 |
| 3| 1000 | 38.58 | 12.82 | 0.60 |
| 5| 1308 | 43.36 | 15.49 | 0.67 |
| 10| 2146 | 55.56 | 22.26 | 0.85 |
| 29| 4897 | 97.55 | 46.57 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5822 | 27.00 | 9.07 | 0.69 |
| 2| 5914 | 35.93 | 12.06 | 0.79 |
| 3| 6127 | 45.80 | 15.44 | 0.90 |
| 4| 6325 | 56.05 | 18.92 | 1.02 |
| 5| 6241 | 59.47 | 19.92 | 1.05 |
| 6| 6608 | 75.24 | 25.41 | 1.23 |
| 7| 6532 | 77.70 | 25.99 | 1.25 |
| 8| 6851 | 93.02 | 31.35 | 1.43 |
| 9| 7005 | 98.41 | 33.19 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 568 | 6172 | 41.02 | 14.97 | 0.86 |
| 10 | 20 | 1137 | 6511 | 61.50 | 23.05 | 1.10 |
| 10 | 30 | 1709 | 6856 | 80.92 | 30.76 | 1.33 |
| 10 | 40 | 2277 | 7193 | 99.66 | 38.24 | 1.55 |

