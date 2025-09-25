--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-09-25 04:15:39.67790799 UTC |
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
| 1| 5837 | 10.36 | 3.28 | 0.51 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6236 | 14.50 | 4.58 | 0.57 |
| 5| 6640 | 18.72 | 5.91 | 0.64 |
| 10| 7651 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 751 | 43.96 | 12.60 | 0.63 |
| 4 | 227 | 858 | 52.51 | 15.02 | 0.72 |
| 5 | 284 | 974 | 62.22 | 17.71 | 0.82 |
| 6 | 340 | 1081 | 74.74 | 21.13 | 0.95 |
| 7 | 394 | 1196 | 72.08 | 20.93 | 0.94 |
| 8 | 450 | 1303 | 96.03 | 27.06 | 1.18 |
| 9 | 505 | 1414 | 93.69 | 26.91 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 23.92 | 7.60 | 0.48 |
| 2| 1928 | 25.92 | 8.80 | 0.51 |
| 3| 2059 | 26.87 | 9.75 | 0.53 |
| 5| 2275 | 29.37 | 11.77 | 0.57 |
| 10| 3148 | 39.74 | 18.03 | 0.74 |
| 39| 7410 | 94.56 | 52.59 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.84 | 7.37 | 0.42 |
| 2| 768 | 24.08 | 8.41 | 0.44 |
| 3| 876 | 25.16 | 9.34 | 0.46 |
| 5| 1302 | 31.25 | 12.39 | 0.55 |
| 10| 2019 | 39.56 | 18.04 | 0.69 |
| 39| 6420 | 97.97 | 53.63 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 26.83 | 8.26 | 0.45 |
| 2| 740 | 30.23 | 9.85 | 0.50 |
| 3| 945 | 30.98 | 10.76 | 0.52 |
| 5| 1281 | 34.93 | 13.22 | 0.58 |
| 10| 1954 | 43.40 | 18.91 | 0.72 |
| 37| 6057 | 99.09 | 52.54 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.15 | 0.53 |
| 2| 883 | 36.60 | 11.61 | 0.57 |
| 3| 938 | 37.84 | 12.60 | 0.59 |
| 5| 1271 | 42.49 | 15.24 | 0.66 |
| 10| 2106 | 54.96 | 22.07 | 0.85 |
| 30| 4945 | 99.97 | 47.88 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5803 | 27.09 | 9.09 | 0.69 |
| 2| 5948 | 35.96 | 12.07 | 0.79 |
| 3| 6142 | 46.00 | 15.51 | 0.90 |
| 4| 6163 | 50.43 | 16.89 | 0.95 |
| 5| 6410 | 64.11 | 21.55 | 1.11 |
| 6| 6589 | 73.32 | 24.65 | 1.21 |
| 7| 6544 | 75.41 | 25.29 | 1.23 |
| 8| 6856 | 89.22 | 29.99 | 1.39 |
| 9| 7001 | 96.04 | 32.39 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 10 | 568 | 6172 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6511 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1709 | 6856 | 79.78 | 30.37 | 1.32 |
| 10 | 38 | 2163 | 7125 | 96.00 | 36.77 | 1.50 |

