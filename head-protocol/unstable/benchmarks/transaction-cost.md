--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-07 04:15:00.846400548 UTC |
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
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 29.40 | 9.28 | 0.79 |
| 43| 14279 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 171 | 747 | 39.97 | 11.62 | 0.59 |
| 4 | 224 | 858 | 48.43 | 14.07 | 0.68 |
| 5 | 283 | 969 | 64.43 | 18.24 | 0.84 |
| 6 | 338 | 1081 | 72.75 | 20.65 | 0.93 |
| 7 | 395 | 1192 | 85.12 | 24.06 | 1.06 |
| 8 | 450 | 1303 | 91.57 | 25.95 | 1.13 |
| 9 | 504 | 1414 | 90.59 | 26.10 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 24.37 | 7.71 | 0.48 |
| 2| 1928 | 25.92 | 8.80 | 0.51 |
| 3| 2131 | 28.17 | 10.11 | 0.54 |
| 5| 2444 | 32.44 | 12.63 | 0.61 |
| 10| 3099 | 39.56 | 17.96 | 0.74 |
| 39| 7430 | 96.53 | 53.11 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 22.77 | 7.36 | 0.42 |
| 2| 771 | 24.28 | 8.45 | 0.44 |
| 3| 975 | 26.13 | 9.61 | 0.47 |
| 5| 1247 | 30.83 | 12.28 | 0.54 |
| 10| 2226 | 45.34 | 19.65 | 0.76 |
| 41| 6789 | 99.63 | 55.41 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.79 | 8.25 | 0.45 |
| 2| 833 | 29.22 | 9.61 | 0.49 |
| 3| 1048 | 32.32 | 11.18 | 0.54 |
| 5| 1263 | 35.12 | 13.27 | 0.59 |
| 10| 1941 | 46.65 | 19.81 | 0.76 |
| 34| 5988 | 98.09 | 50.39 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 691 | 33.83 | 10.16 | 0.53 |
| 2| 760 | 35.17 | 11.17 | 0.55 |
| 3| 949 | 37.80 | 12.59 | 0.59 |
| 5| 1254 | 42.56 | 15.26 | 0.66 |
| 10| 2069 | 54.69 | 22.00 | 0.84 |
| 30| 4965 | 99.95 | 47.90 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5834 | 27.08 | 9.09 | 0.69 |
| 2| 5827 | 31.52 | 10.49 | 0.74 |
| 3| 6003 | 41.52 | 13.91 | 0.85 |
| 4| 6215 | 54.16 | 18.21 | 0.99 |
| 5| 6445 | 64.97 | 21.88 | 1.12 |
| 6| 6482 | 72.38 | 24.28 | 1.20 |
| 7| 6824 | 84.85 | 28.59 | 1.34 |
| 8| 6888 | 92.96 | 31.39 | 1.43 |
| 9| 6875 | 96.65 | 32.48 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6513 | 58.66 | 22.07 | 1.07 |
| 10 | 39 | 2216 | 7155 | 98.49 | 37.73 | 1.53 |

