--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-03 04:38:17.343573809 UTC |
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
| 1| 5834 | 10.19 | 3.22 | 0.51 |
| 2| 6039 | 12.99 | 4.13 | 0.55 |
| 3| 6243 | 14.50 | 4.58 | 0.58 |
| 5| 6641 | 19.19 | 6.08 | 0.64 |
| 10| 7646 | 29.23 | 9.22 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10036 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 170 | 747 | 43.76 | 12.53 | 0.63 |
| 4 | 226 | 858 | 51.35 | 14.79 | 0.71 |
| 5 | 281 | 969 | 59.25 | 17.06 | 0.79 |
| 6 | 339 | 1085 | 68.19 | 19.60 | 0.89 |
| 7 | 393 | 1192 | 82.52 | 23.39 | 1.04 |
| 8 | 449 | 1303 | 96.02 | 27.06 | 1.18 |
| 9 | 506 | 1414 | 90.05 | 26.10 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1792 | 24.29 | 7.69 | 0.48 |
| 2| 1940 | 25.80 | 8.77 | 0.51 |
| 3| 2097 | 28.43 | 10.17 | 0.55 |
| 5| 2438 | 31.95 | 12.51 | 0.61 |
| 10| 3117 | 39.66 | 17.99 | 0.74 |
| 40| 7650 | 97.81 | 54.12 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 609 | 22.84 | 7.38 | 0.41 |
| 2| 808 | 25.12 | 8.70 | 0.45 |
| 3| 967 | 26.64 | 9.79 | 0.48 |
| 5| 1309 | 31.29 | 12.39 | 0.55 |
| 10| 2117 | 43.42 | 19.10 | 0.73 |
| 43| 6755 | 99.83 | 56.78 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 646 | 29.17 | 8.91 | 0.48 |
| 2| 816 | 29.18 | 9.60 | 0.49 |
| 3| 872 | 32.04 | 11.02 | 0.53 |
| 5| 1260 | 36.95 | 13.76 | 0.60 |
| 10| 2117 | 48.83 | 20.46 | 0.79 |
| 35| 5853 | 95.28 | 50.19 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.87 | 10.16 | 0.53 |
| 2| 844 | 36.60 | 11.61 | 0.57 |
| 3| 1033 | 38.55 | 12.81 | 0.60 |
| 5| 1251 | 42.64 | 15.28 | 0.66 |
| 10| 1971 | 53.23 | 21.56 | 0.82 |
| 30| 4828 | 98.56 | 47.49 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 27.00 | 9.08 | 0.69 |
| 2| 5916 | 34.79 | 11.64 | 0.78 |
| 3| 6112 | 44.96 | 15.12 | 0.89 |
| 4| 6301 | 56.01 | 18.97 | 1.02 |
| 5| 6260 | 59.46 | 19.95 | 1.05 |
| 6| 6555 | 73.73 | 24.78 | 1.21 |
| 7| 6650 | 79.78 | 26.81 | 1.28 |
| 8| 6776 | 90.96 | 30.64 | 1.40 |
| 9| 6856 | 90.99 | 30.55 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1710 | 6857 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2218 | 7158 | 98.93 | 37.88 | 1.54 |

