--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-03 04:42:19.47631489 UTC |
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
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 15.22 | 4.84 | 0.58 |
| 5| 6641 | 18.71 | 5.91 | 0.64 |
| 10| 7650 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 637 | 33.25 | 9.63 | 0.52 |
| 3 | 170 | 747 | 42.60 | 12.24 | 0.62 |
| 4 | 225 | 858 | 49.73 | 14.38 | 0.69 |
| 5 | 282 | 969 | 57.89 | 16.73 | 0.78 |
| 6 | 339 | 1081 | 73.81 | 20.95 | 0.95 |
| 7 | 395 | 1192 | 84.83 | 23.98 | 1.06 |
| 8 | 448 | 1303 | 89.50 | 25.55 | 1.11 |
| 10 | 560 | 1525 | 98.64 | 28.62 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1809 | 23.92 | 7.60 | 0.48 |
| 2| 1886 | 24.85 | 8.50 | 0.50 |
| 3| 2059 | 26.90 | 9.76 | 0.53 |
| 5| 2443 | 32.49 | 12.64 | 0.61 |
| 10| 3135 | 40.38 | 18.20 | 0.75 |
| 39| 7546 | 97.24 | 53.37 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.81 | 7.37 | 0.42 |
| 2| 764 | 23.59 | 8.23 | 0.43 |
| 3| 897 | 25.56 | 9.48 | 0.46 |
| 5| 1331 | 32.36 | 12.70 | 0.56 |
| 10| 1955 | 39.16 | 17.93 | 0.68 |
| 42| 6828 | 98.57 | 55.79 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.13 | 8.90 | 0.48 |
| 2| 812 | 29.15 | 9.59 | 0.49 |
| 3| 944 | 30.98 | 10.76 | 0.52 |
| 5| 1218 | 34.67 | 13.14 | 0.58 |
| 10| 2137 | 46.29 | 19.79 | 0.76 |
| 35| 5757 | 99.90 | 51.38 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.83 | 10.15 | 0.53 |
| 2| 761 | 35.14 | 11.16 | 0.55 |
| 3| 896 | 37.20 | 12.40 | 0.58 |
| 5| 1309 | 43.32 | 15.49 | 0.67 |
| 10| 2167 | 55.37 | 22.21 | 0.85 |
| 30| 4969 | 99.11 | 47.64 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.05 | 9.07 | 0.69 |
| 2| 5846 | 31.52 | 10.48 | 0.74 |
| 3| 6070 | 44.94 | 15.09 | 0.89 |
| 4| 6179 | 50.52 | 16.94 | 0.95 |
| 5| 6453 | 65.27 | 22.02 | 1.12 |
| 6| 6355 | 65.40 | 21.89 | 1.12 |
| 7| 6635 | 74.75 | 25.11 | 1.23 |
| 8| 6833 | 93.17 | 31.39 | 1.43 |
| 9| 6861 | 93.89 | 31.49 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.71 | 7.04 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 568 | 6172 | 38.81 | 14.21 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1706 | 6852 | 80.67 | 30.67 | 1.32 |
| 10 | 40 | 2278 | 7195 | 99.66 | 38.24 | 1.55 |
| 10 | 38 | 2162 | 7124 | 95.56 | 36.62 | 1.50 |

