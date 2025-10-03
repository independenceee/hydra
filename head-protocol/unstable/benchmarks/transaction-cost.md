--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-03 04:17:18.429626652 UTC |
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
| 1| 5840 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 12.61 | 4.00 | 0.55 |
| 3| 6242 | 14.90 | 4.72 | 0.58 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 170 | 747 | 43.53 | 12.46 | 0.62 |
| 4 | 224 | 858 | 53.93 | 15.39 | 0.73 |
| 5 | 283 | 969 | 56.39 | 16.34 | 0.77 |
| 6 | 339 | 1081 | 70.40 | 20.04 | 0.91 |
| 7 | 394 | 1192 | 84.25 | 23.80 | 1.05 |
| 8 | 449 | 1303 | 96.94 | 27.34 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1799 | 23.92 | 7.60 | 0.48 |
| 2| 1886 | 24.43 | 8.40 | 0.49 |
| 3| 2156 | 29.02 | 10.36 | 0.55 |
| 5| 2454 | 32.15 | 12.56 | 0.61 |
| 10| 3226 | 42.04 | 18.64 | 0.77 |
| 38| 7395 | 97.02 | 52.57 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.84 | 7.39 | 0.41 |
| 2| 835 | 25.53 | 8.80 | 0.46 |
| 3| 862 | 24.11 | 9.04 | 0.45 |
| 5| 1276 | 30.06 | 12.05 | 0.54 |
| 10| 1996 | 40.20 | 18.24 | 0.69 |
| 41| 6674 | 98.07 | 54.97 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 29.17 | 8.91 | 0.48 |
| 2| 831 | 29.22 | 9.61 | 0.49 |
| 3| 952 | 30.90 | 10.74 | 0.52 |
| 5| 1324 | 35.38 | 13.35 | 0.59 |
| 10| 2110 | 45.56 | 19.57 | 0.75 |
| 37| 6025 | 97.91 | 52.22 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 33.83 | 10.15 | 0.53 |
| 2| 864 | 36.56 | 11.60 | 0.57 |
| 3| 976 | 37.88 | 12.61 | 0.59 |
| 5| 1317 | 43.36 | 15.49 | 0.67 |
| 10| 1947 | 53.16 | 21.54 | 0.82 |
| 29| 4928 | 99.03 | 47.02 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.93 | 7.56 | 0.64 |
| 2| 5915 | 35.93 | 12.07 | 0.79 |
| 3| 6052 | 41.33 | 13.82 | 0.85 |
| 4| 6190 | 51.51 | 17.32 | 0.96 |
| 5| 6285 | 60.67 | 20.32 | 1.06 |
| 6| 6571 | 70.52 | 23.69 | 1.18 |
| 7| 6708 | 82.46 | 27.71 | 1.31 |
| 8| 6960 | 94.99 | 32.10 | 1.46 |
| 9| 6942 | 96.63 | 32.51 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1137 | 6511 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1709 | 6856 | 79.15 | 30.16 | 1.31 |
| 10 | 38 | 2166 | 7128 | 97.77 | 37.38 | 1.52 |

