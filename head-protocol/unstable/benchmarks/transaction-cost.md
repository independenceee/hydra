--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-16 04:50:58.421224178 UTC |
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
| 1| 5836 | 10.26 | 3.25 | 0.51 |
| 2| 6035 | 12.44 | 3.94 | 0.54 |
| 3| 6236 | 14.50 | 4.58 | 0.57 |
| 5| 6646 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 42.49 | 12.21 | 0.61 |
| 4 | 227 | 858 | 54.08 | 15.42 | 0.74 |
| 5 | 284 | 969 | 62.86 | 17.92 | 0.83 |
| 6 | 338 | 1081 | 64.79 | 18.79 | 0.86 |
| 7 | 393 | 1192 | 86.05 | 24.46 | 1.07 |
| 8 | 451 | 1303 | 90.47 | 25.89 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1799 | 24.37 | 7.71 | 0.48 |
| 2| 1924 | 25.47 | 8.69 | 0.50 |
| 3| 2122 | 27.98 | 10.06 | 0.54 |
| 5| 2317 | 30.41 | 12.06 | 0.58 |
| 10| 3244 | 42.41 | 18.77 | 0.77 |
| 40| 7670 | 99.12 | 54.53 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 22.54 | 7.30 | 0.41 |
| 2| 808 | 25.20 | 8.71 | 0.45 |
| 3| 940 | 26.91 | 9.86 | 0.48 |
| 5| 1211 | 29.06 | 11.77 | 0.52 |
| 10| 2031 | 40.82 | 18.39 | 0.70 |
| 40| 6443 | 95.93 | 53.70 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.46 | 8.69 | 0.47 |
| 2| 861 | 29.86 | 9.81 | 0.50 |
| 3| 916 | 32.76 | 11.24 | 0.54 |
| 5| 1282 | 37.66 | 13.98 | 0.61 |
| 10| 2005 | 47.36 | 20.02 | 0.77 |
| 36| 6057 | 97.93 | 51.64 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 672 | 33.87 | 10.16 | 0.53 |
| 2| 820 | 35.89 | 11.39 | 0.56 |
| 3| 938 | 37.88 | 12.61 | 0.59 |
| 5| 1270 | 42.72 | 15.30 | 0.66 |
| 10| 1983 | 53.42 | 21.61 | 0.82 |
| 28| 5049 | 99.57 | 46.55 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.00 | 9.06 | 0.69 |
| 2| 5916 | 34.83 | 11.65 | 0.78 |
| 3| 6038 | 41.21 | 13.79 | 0.85 |
| 4| 6250 | 55.07 | 18.54 | 1.00 |
| 5| 6283 | 59.72 | 20.03 | 1.05 |
| 6| 6649 | 75.53 | 25.52 | 1.24 |
| 7| 6743 | 83.01 | 28.06 | 1.32 |
| 8| 6881 | 90.28 | 30.56 | 1.40 |
| 9| 6839 | 97.51 | 32.74 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 568 | 6173 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2161 | 7123 | 96.88 | 37.08 | 1.51 |

