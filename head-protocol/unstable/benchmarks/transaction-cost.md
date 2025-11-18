--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-18 04:19:10.281006309 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6035 | 12.46 | 3.94 | 0.54 |
| 3| 6236 | 14.81 | 4.69 | 0.58 |
| 5| 6638 | 19.08 | 6.04 | 0.64 |
| 10| 7651 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10049 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 169 | 747 | 40.10 | 11.64 | 0.59 |
| 4 | 226 | 858 | 52.47 | 15.03 | 0.72 |
| 5 | 283 | 969 | 62.57 | 17.82 | 0.83 |
| 6 | 339 | 1081 | 75.83 | 21.47 | 0.97 |
| 7 | 392 | 1192 | 83.28 | 23.66 | 1.05 |
| 8 | 450 | 1303 | 84.45 | 24.24 | 1.06 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1823 | 24.00 | 7.62 | 0.48 |
| 2| 1930 | 25.47 | 8.70 | 0.50 |
| 3| 2012 | 26.24 | 9.56 | 0.52 |
| 5| 2398 | 30.96 | 12.23 | 0.59 |
| 10| 3233 | 42.89 | 18.89 | 0.78 |
| 39| 7697 | 99.09 | 53.86 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 619 | 22.84 | 7.38 | 0.42 |
| 2| 829 | 25.40 | 8.78 | 0.46 |
| 3| 885 | 25.12 | 9.34 | 0.46 |
| 5| 1229 | 30.94 | 12.32 | 0.54 |
| 10| 2088 | 42.07 | 18.74 | 0.72 |
| 39| 6185 | 92.43 | 52.08 | 1.54 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.54 | 8.47 | 0.46 |
| 2| 812 | 29.26 | 9.62 | 0.49 |
| 3| 903 | 30.23 | 10.54 | 0.51 |
| 5| 1250 | 34.93 | 13.22 | 0.58 |
| 10| 1951 | 46.54 | 19.78 | 0.75 |
| 36| 5962 | 96.52 | 51.20 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 814 | 35.92 | 11.40 | 0.56 |
| 3| 980 | 38.55 | 12.81 | 0.60 |
| 5| 1281 | 42.57 | 15.26 | 0.66 |
| 10| 1952 | 53.20 | 21.55 | 0.82 |
| 30| 5039 | 99.93 | 47.91 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 27.09 | 9.10 | 0.69 |
| 2| 6033 | 36.89 | 12.44 | 0.80 |
| 3| 6065 | 43.40 | 14.56 | 0.87 |
| 4| 6225 | 54.00 | 18.17 | 0.99 |
| 5| 6379 | 61.26 | 20.63 | 1.07 |
| 6| 6478 | 70.12 | 23.56 | 1.17 |
| 7| 6578 | 79.08 | 26.59 | 1.27 |
| 8| 7021 | 92.47 | 31.18 | 1.43 |
| 9| 6975 | 98.42 | 33.11 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.91 | 22.51 | 1.08 |
| 10 | 39 | 2220 | 7159 | 97.61 | 37.43 | 1.52 |

