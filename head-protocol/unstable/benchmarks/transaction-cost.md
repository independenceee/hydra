--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-02 04:52:11.950272846 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.88 | 4.72 | 0.58 |
| 5| 6641 | 18.81 | 5.94 | 0.64 |
| 10| 7647 | 29.23 | 9.22 | 0.79 |
| 43| 14282 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 640 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 41.11 | 11.90 | 0.60 |
| 4 | 228 | 862 | 48.45 | 14.07 | 0.68 |
| 5 | 284 | 969 | 56.16 | 16.29 | 0.76 |
| 6 | 338 | 1081 | 73.74 | 20.96 | 0.94 |
| 7 | 396 | 1192 | 84.72 | 23.96 | 1.06 |
| 8 | 449 | 1307 | 82.51 | 23.77 | 1.05 |
| 9 | 507 | 1414 | 94.46 | 27.04 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1746 | 22.92 | 7.32 | 0.47 |
| 2| 1991 | 26.62 | 9.02 | 0.52 |
| 3| 2013 | 25.95 | 9.49 | 0.52 |
| 5| 2503 | 32.38 | 12.63 | 0.61 |
| 10| 3205 | 41.74 | 18.57 | 0.76 |
| 41| 7638 | 97.62 | 54.74 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.50 | 7.29 | 0.41 |
| 2| 812 | 25.20 | 8.72 | 0.45 |
| 3| 948 | 26.90 | 9.86 | 0.48 |
| 5| 1247 | 30.93 | 12.31 | 0.54 |
| 10| 2173 | 43.95 | 19.27 | 0.74 |
| 42| 6663 | 98.08 | 55.62 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 661 | 29.09 | 8.89 | 0.48 |
| 2| 801 | 30.94 | 10.07 | 0.51 |
| 3| 910 | 32.68 | 11.22 | 0.54 |
| 5| 1289 | 34.89 | 13.21 | 0.58 |
| 10| 2190 | 46.77 | 19.95 | 0.77 |
| 37| 6053 | 99.16 | 52.57 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.16 | 0.53 |
| 2| 833 | 35.92 | 11.40 | 0.56 |
| 3| 937 | 37.87 | 12.61 | 0.59 |
| 5| 1312 | 43.50 | 15.55 | 0.67 |
| 10| 2121 | 55.71 | 22.30 | 0.85 |
| 30| 5001 | 99.95 | 47.89 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.05 | 9.07 | 0.69 |
| 2| 5890 | 32.53 | 10.86 | 0.75 |
| 3| 6217 | 47.21 | 15.93 | 0.92 |
| 4| 6274 | 54.88 | 18.55 | 1.00 |
| 5| 6354 | 60.74 | 20.38 | 1.07 |
| 6| 6576 | 73.86 | 24.86 | 1.22 |
| 7| 6605 | 79.42 | 26.63 | 1.27 |
| 8| 6887 | 89.67 | 30.22 | 1.40 |
| 9| 6892 | 93.50 | 31.43 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1704 | 6851 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2216 | 7156 | 97.61 | 37.43 | 1.52 |

