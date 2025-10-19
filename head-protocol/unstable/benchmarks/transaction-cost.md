--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-19 04:30:53.432084355 UTC |
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
| 1| 5837 | 10.57 | 3.36 | 0.52 |
| 2| 6037 | 12.53 | 3.97 | 0.55 |
| 3| 6239 | 14.60 | 4.62 | 0.58 |
| 5| 6641 | 18.83 | 5.95 | 0.64 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 169 | 747 | 40.22 | 11.69 | 0.59 |
| 4 | 225 | 858 | 52.47 | 15.01 | 0.72 |
| 5 | 283 | 969 | 62.56 | 17.82 | 0.83 |
| 6 | 337 | 1081 | 71.97 | 20.54 | 0.93 |
| 7 | 394 | 1196 | 72.51 | 20.99 | 0.94 |
| 8 | 450 | 1303 | 89.33 | 25.36 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.37 | 7.71 | 0.48 |
| 2| 1997 | 26.55 | 9.00 | 0.52 |
| 3| 2128 | 28.69 | 10.26 | 0.55 |
| 5| 2315 | 30.08 | 11.98 | 0.58 |
| 10| 3180 | 40.80 | 18.32 | 0.75 |
| 41| 7836 | 99.69 | 55.36 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 642 | 22.54 | 7.30 | 0.41 |
| 2| 697 | 22.55 | 7.93 | 0.42 |
| 3| 911 | 25.52 | 9.47 | 0.46 |
| 5| 1302 | 32.27 | 12.66 | 0.56 |
| 10| 1998 | 39.40 | 18.00 | 0.69 |
| 40| 6468 | 97.62 | 54.17 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 29.17 | 8.91 | 0.48 |
| 2| 736 | 30.19 | 9.84 | 0.50 |
| 3| 972 | 33.43 | 11.44 | 0.55 |
| 5| 1172 | 36.35 | 13.57 | 0.59 |
| 10| 2016 | 47.93 | 20.20 | 0.77 |
| 37| 5868 | 97.11 | 51.98 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.15 | 0.53 |
| 2| 807 | 35.85 | 11.38 | 0.56 |
| 3| 965 | 37.87 | 12.61 | 0.59 |
| 5| 1241 | 42.68 | 15.29 | 0.66 |
| 10| 2249 | 56.69 | 22.62 | 0.87 |
| 28| 4943 | 98.01 | 46.14 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.05 | 9.07 | 0.69 |
| 2| 5961 | 35.87 | 12.05 | 0.79 |
| 3| 6061 | 44.69 | 15.03 | 0.89 |
| 4| 6256 | 51.50 | 17.29 | 0.97 |
| 5| 6384 | 64.13 | 21.57 | 1.10 |
| 6| 6340 | 65.47 | 21.90 | 1.12 |
| 7| 6676 | 81.51 | 27.47 | 1.30 |
| 8| 6967 | 90.37 | 30.47 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.38 | 6.48 | 0.61 |
| 10 | 10 | 568 | 6172 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 40 | 2276 | 7192 | 99.22 | 38.09 | 1.54 |

