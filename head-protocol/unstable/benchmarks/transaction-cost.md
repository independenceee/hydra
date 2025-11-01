--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-01 04:16:35.479181898 UTC |
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
| 1| 5834 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6645 | 18.83 | 5.95 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10047 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 40.20 | 11.68 | 0.59 |
| 4 | 228 | 858 | 52.59 | 15.06 | 0.72 |
| 5 | 283 | 969 | 56.31 | 16.35 | 0.77 |
| 6 | 337 | 1081 | 71.65 | 20.39 | 0.92 |
| 7 | 394 | 1192 | 84.16 | 23.77 | 1.05 |
| 8 | 450 | 1303 | 94.59 | 26.77 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 22.92 | 7.32 | 0.47 |
| 2| 1958 | 26.96 | 9.09 | 0.52 |
| 3| 2061 | 27.43 | 9.89 | 0.53 |
| 5| 2401 | 32.52 | 12.65 | 0.61 |
| 10| 3168 | 40.73 | 18.30 | 0.75 |
| 41| 7600 | 97.02 | 54.58 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.50 | 7.29 | 0.41 |
| 2| 785 | 25.52 | 8.79 | 0.45 |
| 3| 910 | 25.79 | 9.54 | 0.47 |
| 5| 1185 | 29.62 | 11.95 | 0.53 |
| 10| 2049 | 39.61 | 18.05 | 0.69 |
| 43| 6834 | 99.95 | 56.83 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 27.47 | 8.46 | 0.46 |
| 2| 859 | 29.86 | 9.81 | 0.50 |
| 3| 910 | 32.64 | 11.21 | 0.53 |
| 5| 1315 | 35.65 | 13.44 | 0.59 |
| 10| 1868 | 46.06 | 19.62 | 0.75 |
| 36| 5973 | 96.95 | 51.32 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.16 | 0.53 |
| 2| 761 | 35.17 | 11.17 | 0.55 |
| 3| 962 | 37.87 | 12.61 | 0.59 |
| 5| 1338 | 43.43 | 15.51 | 0.67 |
| 10| 1961 | 53.53 | 21.64 | 0.83 |
| 29| 4664 | 95.99 | 46.07 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5824 | 26.96 | 9.06 | 0.69 |
| 2| 5916 | 34.79 | 11.64 | 0.78 |
| 3| 6114 | 45.85 | 15.45 | 0.90 |
| 4| 6144 | 53.20 | 17.84 | 0.98 |
| 5| 6368 | 64.43 | 21.68 | 1.11 |
| 6| 6645 | 74.88 | 25.29 | 1.23 |
| 7| 6708 | 84.15 | 28.38 | 1.33 |
| 8| 6741 | 83.96 | 28.26 | 1.33 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2220 | 7160 | 98.49 | 37.73 | 1.53 |

