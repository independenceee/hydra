--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-13 04:35:54.065912104 UTC |
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
| 2| 6038 | 12.42 | 3.93 | 0.54 |
| 3| 6239 | 14.47 | 4.57 | 0.57 |
| 5| 6641 | 18.60 | 5.87 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.40 | 9.67 | 0.52 |
| 3 | 170 | 747 | 42.84 | 12.34 | 0.62 |
| 4 | 226 | 858 | 54.01 | 15.40 | 0.74 |
| 5 | 282 | 969 | 56.67 | 16.47 | 0.77 |
| 6 | 338 | 1081 | 64.36 | 18.64 | 0.85 |
| 7 | 392 | 1192 | 78.57 | 22.48 | 1.00 |
| 8 | 449 | 1303 | 86.02 | 24.77 | 1.08 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1812 | 24.00 | 7.62 | 0.48 |
| 2| 1928 | 25.47 | 8.70 | 0.50 |
| 3| 2072 | 27.32 | 9.86 | 0.53 |
| 5| 2387 | 31.49 | 12.36 | 0.60 |
| 10| 3092 | 39.87 | 18.04 | 0.74 |
| 38| 7541 | 96.75 | 52.55 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 22.77 | 7.37 | 0.42 |
| 2| 791 | 23.98 | 8.38 | 0.44 |
| 3| 900 | 25.14 | 9.33 | 0.46 |
| 5| 1320 | 31.06 | 12.32 | 0.55 |
| 10| 2026 | 40.58 | 18.34 | 0.70 |
| 40| 6537 | 99.39 | 54.68 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 29.13 | 8.90 | 0.48 |
| 2| 841 | 29.26 | 9.62 | 0.49 |
| 3| 1007 | 31.61 | 10.96 | 0.53 |
| 5| 1248 | 35.01 | 13.24 | 0.58 |
| 10| 1972 | 44.14 | 19.14 | 0.73 |
| 38| 6122 | 99.94 | 53.42 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.79 | 10.15 | 0.53 |
| 2| 836 | 35.92 | 11.40 | 0.56 |
| 3| 980 | 38.55 | 12.81 | 0.60 |
| 5| 1200 | 41.93 | 15.06 | 0.65 |
| 10| 2153 | 55.47 | 22.24 | 0.85 |
| 29| 4898 | 98.76 | 46.92 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.12 | 9.10 | 0.69 |
| 2| 5965 | 36.03 | 12.10 | 0.79 |
| 3| 5971 | 40.51 | 13.53 | 0.84 |
| 4| 6329 | 52.28 | 17.65 | 0.98 |
| 5| 6446 | 66.03 | 22.24 | 1.13 |
| 6| 6468 | 69.28 | 23.29 | 1.16 |
| 7| 6737 | 83.35 | 28.08 | 1.32 |
| 8| 6903 | 91.67 | 30.99 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6004 | 27.58 | 9.82 | 0.71 |
| 10 | 20 | 1139 | 6513 | 60.61 | 22.74 | 1.09 |
| 10 | 30 | 1709 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2278 | 7194 | 99.22 | 38.09 | 1.54 |

