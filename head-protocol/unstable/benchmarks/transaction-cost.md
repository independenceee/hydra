--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-25 04:35:54.111885647 UTC |
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
| 2| 6037 | 12.42 | 3.93 | 0.54 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6638 | 18.72 | 5.91 | 0.64 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10038 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 170 | 747 | 42.34 | 12.17 | 0.61 |
| 4 | 226 | 858 | 49.41 | 14.27 | 0.69 |
| 5 | 283 | 969 | 64.65 | 18.38 | 0.85 |
| 6 | 341 | 1081 | 67.74 | 19.45 | 0.89 |
| 7 | 394 | 1192 | 72.14 | 20.90 | 0.94 |
| 8 | 450 | 1307 | 96.51 | 27.23 | 1.18 |
| 9 | 504 | 1414 | 92.28 | 26.73 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1809 | 24.00 | 7.62 | 0.48 |
| 2| 1970 | 26.39 | 8.96 | 0.51 |
| 3| 2077 | 26.98 | 9.78 | 0.53 |
| 5| 2430 | 32.32 | 12.60 | 0.61 |
| 10| 3222 | 43.23 | 18.99 | 0.78 |
| 39| 7412 | 95.48 | 52.81 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 637 | 22.54 | 7.30 | 0.41 |
| 2| 735 | 24.08 | 8.40 | 0.44 |
| 3| 951 | 26.02 | 9.58 | 0.47 |
| 5| 1227 | 29.15 | 11.79 | 0.52 |
| 10| 1967 | 38.38 | 17.71 | 0.67 |
| 41| 6832 | 99.55 | 55.42 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 27.50 | 8.46 | 0.46 |
| 2| 785 | 30.94 | 10.07 | 0.51 |
| 3| 961 | 33.51 | 11.47 | 0.55 |
| 5| 1232 | 37.10 | 13.79 | 0.60 |
| 10| 2084 | 48.90 | 20.48 | 0.78 |
| 39| 6013 | 97.54 | 53.35 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 850 | 36.64 | 11.62 | 0.57 |
| 3| 891 | 37.13 | 12.38 | 0.58 |
| 5| 1198 | 41.78 | 15.02 | 0.65 |
| 10| 1945 | 52.74 | 21.40 | 0.82 |
| 30| 4769 | 97.75 | 47.21 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.08 | 9.09 | 0.69 |
| 2| 6003 | 36.96 | 12.48 | 0.80 |
| 3| 6095 | 44.85 | 15.06 | 0.89 |
| 4| 6252 | 54.45 | 18.38 | 1.00 |
| 5| 6376 | 61.80 | 20.85 | 1.08 |
| 6| 6529 | 70.51 | 23.74 | 1.18 |
| 7| 6673 | 79.74 | 26.82 | 1.28 |
| 8| 6915 | 90.48 | 30.47 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 283 | 6002 | 30.23 | 10.73 | 0.74 |
| 10 | 20 | 1139 | 6513 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1705 | 6851 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2224 | 7164 | 99.56 | 38.10 | 1.54 |

