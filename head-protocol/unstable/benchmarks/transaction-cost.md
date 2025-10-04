--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-04 04:14:52.020062935 UTC |
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
| 1| 5840 | 10.36 | 3.28 | 0.51 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.60 | 5.87 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 751 | 43.74 | 12.55 | 0.63 |
| 4 | 227 | 858 | 52.47 | 15.01 | 0.72 |
| 5 | 282 | 969 | 58.87 | 16.90 | 0.79 |
| 6 | 338 | 1081 | 75.12 | 21.19 | 0.96 |
| 7 | 396 | 1196 | 81.67 | 23.17 | 1.03 |
| 8 | 449 | 1303 | 96.55 | 27.19 | 1.18 |
| 9 | 507 | 1414 | 91.75 | 26.50 | 1.14 |
| 10 | 560 | 1529 | 96.93 | 28.20 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1812 | 24.00 | 7.62 | 0.48 |
| 2| 2012 | 26.47 | 8.98 | 0.52 |
| 3| 2017 | 26.36 | 9.59 | 0.52 |
| 5| 2322 | 30.08 | 11.98 | 0.58 |
| 10| 3115 | 41.22 | 18.41 | 0.75 |
| 41| 7685 | 96.62 | 54.48 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 604 | 22.53 | 7.30 | 0.41 |
| 2| 783 | 25.55 | 8.79 | 0.45 |
| 3| 920 | 25.03 | 9.30 | 0.46 |
| 5| 1123 | 27.09 | 11.21 | 0.50 |
| 10| 1912 | 37.51 | 17.46 | 0.66 |
| 41| 6706 | 99.04 | 55.23 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 691 | 27.51 | 8.47 | 0.46 |
| 2| 849 | 31.58 | 10.27 | 0.52 |
| 3| 959 | 30.82 | 10.73 | 0.52 |
| 5| 1251 | 37.14 | 13.81 | 0.60 |
| 10| 1926 | 43.51 | 18.94 | 0.72 |
| 33| 5514 | 91.50 | 47.80 | 1.48 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 33.12 | 9.94 | 0.52 |
| 2| 806 | 35.85 | 11.38 | 0.56 |
| 3| 899 | 37.13 | 12.38 | 0.58 |
| 5| 1327 | 43.43 | 15.51 | 0.67 |
| 10| 1958 | 53.34 | 21.59 | 0.82 |
| 30| 4800 | 98.48 | 47.41 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5785 | 27.00 | 9.07 | 0.69 |
| 2| 5894 | 32.41 | 10.85 | 0.75 |
| 3| 6121 | 45.93 | 15.50 | 0.90 |
| 4| 6252 | 53.74 | 18.09 | 0.99 |
| 5| 6482 | 65.29 | 21.98 | 1.12 |
| 6| 6525 | 73.37 | 24.62 | 1.21 |
| 7| 6710 | 82.15 | 27.64 | 1.31 |
| 8| 6950 | 92.37 | 31.12 | 1.43 |
| 9| 7072 | 97.00 | 32.69 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 16.98 | 5.65 | 0.58 |
| 10 | 1 | 57 | 5868 | 21.41 | 7.28 | 0.63 |
| 10 | 5 | 286 | 6005 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1139 | 6514 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2277 | 7194 | 99.66 | 38.24 | 1.55 |

