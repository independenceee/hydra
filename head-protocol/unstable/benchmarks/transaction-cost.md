--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-16 04:17:48.254549241 UTC |
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
| 1| 5836 | 10.67 | 3.39 | 0.52 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 28.80 | 9.07 | 0.78 |
| 43| 14286 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 914 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10038 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 170 | 747 | 39.85 | 11.58 | 0.59 |
| 4 | 225 | 858 | 48.00 | 13.91 | 0.68 |
| 5 | 284 | 969 | 64.56 | 18.30 | 0.85 |
| 6 | 339 | 1081 | 75.19 | 21.24 | 0.96 |
| 7 | 394 | 1192 | 76.74 | 22.09 | 0.98 |
| 8 | 451 | 1307 | 84.79 | 24.32 | 1.07 |
| 9 | 507 | 1414 | 88.79 | 25.73 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 24.37 | 7.71 | 0.48 |
| 2| 1942 | 25.51 | 8.70 | 0.50 |
| 3| 2079 | 27.33 | 9.89 | 0.53 |
| 5| 2320 | 29.96 | 11.95 | 0.58 |
| 10| 3190 | 41.77 | 18.58 | 0.76 |
| 41| 7644 | 97.14 | 54.63 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.84 | 7.38 | 0.41 |
| 2| 722 | 22.56 | 7.94 | 0.42 |
| 3| 934 | 27.06 | 9.90 | 0.48 |
| 5| 1203 | 29.14 | 11.78 | 0.52 |
| 10| 1905 | 37.35 | 17.42 | 0.66 |
| 42| 6779 | 99.79 | 56.14 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.50 | 8.46 | 0.46 |
| 2| 852 | 31.66 | 10.28 | 0.52 |
| 3| 1054 | 32.24 | 11.16 | 0.54 |
| 5| 1210 | 34.37 | 13.04 | 0.58 |
| 10| 1973 | 44.22 | 19.16 | 0.73 |
| 35| 6057 | 98.12 | 51.03 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 625 | 33.15 | 9.95 | 0.52 |
| 2| 764 | 35.17 | 11.17 | 0.55 |
| 3| 1007 | 38.62 | 12.83 | 0.60 |
| 5| 1331 | 43.21 | 15.46 | 0.67 |
| 10| 2048 | 54.74 | 22.02 | 0.84 |
| 28| 4714 | 96.58 | 45.63 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5803 | 27.13 | 9.10 | 0.69 |
| 2| 5980 | 36.81 | 12.41 | 0.80 |
| 3| 6115 | 44.81 | 15.05 | 0.89 |
| 4| 6127 | 50.38 | 16.85 | 0.95 |
| 5| 6429 | 63.65 | 21.46 | 1.10 |
| 6| 6433 | 68.66 | 22.98 | 1.15 |
| 7| 6804 | 84.98 | 28.68 | 1.34 |
| 8| 6868 | 91.47 | 30.74 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 568 | 6172 | 38.99 | 14.28 | 0.84 |
| 10 | 20 | 1138 | 6513 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1709 | 6855 | 79.78 | 30.37 | 1.32 |
| 10 | 39 | 2217 | 7156 | 99.38 | 38.04 | 1.54 |

