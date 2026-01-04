--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-04 04:59:56.005807055 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6645 | 18.50 | 5.83 | 0.63 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10080 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 41.22 | 11.92 | 0.60 |
| 4 | 226 | 858 | 54.02 | 15.41 | 0.74 |
| 5 | 283 | 969 | 62.32 | 17.73 | 0.82 |
| 6 | 339 | 1081 | 66.86 | 19.36 | 0.88 |
| 7 | 395 | 1192 | 78.23 | 22.36 | 1.00 |
| 8 | 450 | 1303 | 91.33 | 25.89 | 1.13 |
| 9 | 505 | 1414 | 96.73 | 27.69 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.00 | 7.62 | 0.48 |
| 2| 1966 | 26.79 | 9.05 | 0.52 |
| 3| 2013 | 26.36 | 9.59 | 0.52 |
| 5| 2395 | 31.33 | 12.32 | 0.60 |
| 10| 3200 | 42.35 | 18.72 | 0.77 |
| 41| 7812 | 99.32 | 55.26 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 598 | 22.84 | 7.37 | 0.41 |
| 2| 764 | 23.63 | 8.24 | 0.43 |
| 3| 917 | 27.06 | 9.90 | 0.48 |
| 5| 1282 | 30.83 | 12.28 | 0.54 |
| 10| 2125 | 41.61 | 18.61 | 0.71 |
| 40| 6477 | 95.75 | 53.67 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 27.50 | 8.46 | 0.46 |
| 2| 848 | 31.58 | 10.27 | 0.52 |
| 3| 902 | 30.26 | 10.55 | 0.51 |
| 5| 1262 | 34.97 | 13.23 | 0.58 |
| 10| 2116 | 48.90 | 20.48 | 0.79 |
| 37| 6063 | 98.36 | 52.37 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.15 | 0.53 |
| 2| 897 | 36.56 | 11.60 | 0.57 |
| 3| 953 | 37.91 | 12.62 | 0.59 |
| 5| 1225 | 41.93 | 15.06 | 0.65 |
| 10| 2025 | 54.21 | 21.85 | 0.83 |
| 30| 4926 | 99.26 | 47.69 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5807 | 26.92 | 9.04 | 0.69 |
| 2| 5943 | 35.99 | 12.08 | 0.79 |
| 3| 6014 | 41.52 | 13.90 | 0.85 |
| 4| 6188 | 53.58 | 18.07 | 0.99 |
| 5| 6507 | 65.35 | 22.16 | 1.12 |
| 6| 6573 | 73.43 | 24.79 | 1.21 |
| 7| 6514 | 73.77 | 24.72 | 1.21 |
| 8| 6892 | 90.10 | 30.31 | 1.40 |
| 9| 6898 | 94.06 | 31.54 | 1.44 |
| 10| 6859 | 96.20 | 32.15 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.75 | 6.61 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 284 | 6003 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 570 | 6175 | 39.51 | 14.45 | 0.85 |
| 10 | 30 | 1704 | 6850 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2280 | 7196 | 99.66 | 38.24 | 1.55 |

