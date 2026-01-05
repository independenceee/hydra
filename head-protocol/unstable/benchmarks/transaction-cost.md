--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-05 05:07:19.036636926 UTC |
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
| 1| 5834 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6638 | 18.79 | 5.94 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14286 | 99.23 | 31.02 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 43.64 | 12.49 | 0.63 |
| 4 | 227 | 858 | 50.67 | 14.60 | 0.70 |
| 5 | 282 | 969 | 55.69 | 16.17 | 0.76 |
| 6 | 338 | 1081 | 73.98 | 21.02 | 0.95 |
| 7 | 392 | 1192 | 75.52 | 21.89 | 0.97 |
| 8 | 449 | 1303 | 96.28 | 27.17 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1882 | 24.77 | 8.48 | 0.49 |
| 3| 2123 | 28.43 | 10.17 | 0.55 |
| 5| 2332 | 29.93 | 11.94 | 0.58 |
| 10| 3050 | 38.62 | 17.70 | 0.72 |
| 41| 7759 | 98.70 | 55.09 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 22.84 | 7.38 | 0.42 |
| 2| 840 | 25.49 | 8.78 | 0.46 |
| 3| 900 | 25.12 | 9.34 | 0.46 |
| 5| 1236 | 31.01 | 12.33 | 0.54 |
| 10| 1847 | 36.51 | 17.19 | 0.65 |
| 40| 6506 | 96.64 | 53.92 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.50 | 8.46 | 0.46 |
| 2| 733 | 30.23 | 9.85 | 0.50 |
| 3| 868 | 32.05 | 11.02 | 0.53 |
| 5| 1366 | 36.24 | 13.62 | 0.60 |
| 10| 2091 | 49.01 | 20.53 | 0.79 |
| 36| 6010 | 97.83 | 51.60 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.83 | 10.15 | 0.53 |
| 2| 807 | 35.85 | 11.38 | 0.56 |
| 3| 976 | 38.21 | 12.71 | 0.59 |
| 5| 1158 | 41.11 | 14.82 | 0.64 |
| 10| 1967 | 53.60 | 21.67 | 0.83 |
| 29| 4933 | 99.17 | 47.04 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.05 | 9.07 | 0.69 |
| 2| 5935 | 35.83 | 12.03 | 0.79 |
| 3| 5944 | 38.06 | 12.66 | 0.81 |
| 4| 6380 | 56.29 | 19.00 | 1.02 |
| 5| 6382 | 63.88 | 21.51 | 1.10 |
| 6| 6520 | 73.75 | 24.86 | 1.21 |
| 7| 6793 | 85.80 | 28.97 | 1.35 |
| 8| 6805 | 89.62 | 30.16 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.38 | 6.48 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.85 | 7.43 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 37.74 | 13.85 | 0.83 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1704 | 6851 | 78.71 | 30.00 | 1.30 |
| 10 | 39 | 2221 | 7160 | 99.12 | 37.95 | 1.54 |

