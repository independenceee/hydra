--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-10 04:38:30.408510361 UTC |
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
| 1| 5837 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6236 | 14.71 | 4.65 | 0.58 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 58 | 530 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 747 | 40.31 | 11.73 | 0.59 |
| 4 | 227 | 858 | 48.22 | 13.99 | 0.68 |
| 5 | 282 | 974 | 63.94 | 18.12 | 0.84 |
| 6 | 338 | 1081 | 66.81 | 19.31 | 0.88 |
| 7 | 392 | 1192 | 85.43 | 24.21 | 1.07 |
| 8 | 449 | 1303 | 93.50 | 26.41 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1802 | 24.00 | 7.62 | 0.48 |
| 2| 1931 | 25.76 | 8.76 | 0.51 |
| 3| 2014 | 25.95 | 9.49 | 0.52 |
| 5| 2511 | 33.18 | 12.85 | 0.62 |
| 10| 3155 | 40.85 | 18.31 | 0.75 |
| 40| 7687 | 98.16 | 54.27 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 22.81 | 7.37 | 0.42 |
| 2| 836 | 25.57 | 8.80 | 0.46 |
| 3| 896 | 25.02 | 9.30 | 0.46 |
| 5| 1290 | 30.15 | 12.07 | 0.54 |
| 10| 1968 | 37.66 | 17.50 | 0.67 |
| 41| 6685 | 97.90 | 54.96 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 27.50 | 8.46 | 0.46 |
| 2| 766 | 28.51 | 9.39 | 0.48 |
| 3| 963 | 30.90 | 10.74 | 0.52 |
| 5| 1338 | 38.26 | 14.16 | 0.62 |
| 10| 1910 | 43.37 | 18.91 | 0.72 |
| 36| 5890 | 97.31 | 51.40 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 872 | 36.64 | 11.62 | 0.57 |
| 3| 999 | 38.62 | 12.83 | 0.60 |
| 5| 1316 | 43.40 | 15.50 | 0.67 |
| 10| 2045 | 54.42 | 21.94 | 0.84 |
| 29| 5033 | 99.83 | 47.26 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5780 | 27.13 | 9.09 | 0.69 |
| 2| 5891 | 34.79 | 11.64 | 0.77 |
| 3| 5968 | 40.58 | 13.53 | 0.84 |
| 4| 6144 | 50.32 | 16.89 | 0.95 |
| 5| 6448 | 64.96 | 21.90 | 1.12 |
| 6| 6560 | 73.74 | 24.83 | 1.21 |
| 7| 6819 | 85.00 | 28.75 | 1.34 |
| 8| 6685 | 86.79 | 29.11 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.85 | 7.43 | 0.64 |
| 10 | 5 | 285 | 6005 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 571 | 6176 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6513 | 58.21 | 21.92 | 1.07 |
| 10 | 30 | 1708 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2217 | 7156 | 99.82 | 38.19 | 1.55 |

