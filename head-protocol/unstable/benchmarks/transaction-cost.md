--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-24 04:16:47.549117573 UTC |
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
| 1| 5836 | 10.48 | 3.33 | 0.52 |
| 2| 6035 | 12.78 | 4.06 | 0.55 |
| 3| 6243 | 14.76 | 4.67 | 0.58 |
| 5| 6638 | 18.58 | 5.86 | 0.63 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14286 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10084 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 171 | 747 | 43.64 | 12.50 | 0.63 |
| 4 | 227 | 858 | 48.30 | 14.01 | 0.68 |
| 5 | 284 | 974 | 57.60 | 16.63 | 0.78 |
| 6 | 339 | 1081 | 73.58 | 20.86 | 0.94 |
| 7 | 395 | 1196 | 75.06 | 21.69 | 0.97 |
| 8 | 452 | 1303 | 94.90 | 26.85 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1746 | 22.93 | 7.32 | 0.47 |
| 2| 1882 | 24.80 | 8.49 | 0.49 |
| 3| 2054 | 27.27 | 9.85 | 0.53 |
| 5| 2498 | 33.71 | 12.99 | 0.63 |
| 10| 3057 | 39.91 | 18.05 | 0.74 |
| 40| 7715 | 98.57 | 54.40 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.80 | 7.37 | 0.41 |
| 2| 798 | 25.47 | 8.77 | 0.45 |
| 3| 902 | 25.45 | 9.45 | 0.46 |
| 5| 1225 | 29.01 | 11.75 | 0.52 |
| 10| 2087 | 39.58 | 18.04 | 0.69 |
| 40| 6556 | 99.72 | 54.76 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.09 | 8.89 | 0.48 |
| 2| 850 | 31.69 | 10.29 | 0.52 |
| 3| 915 | 32.68 | 11.22 | 0.54 |
| 5| 1230 | 36.95 | 13.76 | 0.60 |
| 10| 1945 | 46.54 | 19.78 | 0.75 |
| 38| 6127 | 98.78 | 53.15 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.83 | 10.16 | 0.53 |
| 2| 809 | 35.89 | 11.39 | 0.56 |
| 3| 942 | 37.87 | 12.61 | 0.59 |
| 5| 1196 | 41.97 | 15.07 | 0.65 |
| 10| 2011 | 53.90 | 21.77 | 0.83 |
| 30| 4789 | 96.92 | 47.00 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5780 | 27.13 | 9.09 | 0.69 |
| 2| 5929 | 35.89 | 12.06 | 0.79 |
| 3| 6112 | 44.55 | 15.00 | 0.89 |
| 4| 6299 | 54.88 | 18.50 | 1.00 |
| 5| 6328 | 60.53 | 20.35 | 1.06 |
| 6| 6670 | 74.68 | 25.26 | 1.23 |
| 7| 6703 | 80.58 | 27.09 | 1.29 |
| 8| 6704 | 88.26 | 29.67 | 1.37 |
| 9| 6890 | 92.40 | 31.02 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 570 | 6175 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6512 | 60.61 | 22.74 | 1.09 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2221 | 7160 | 98.49 | 37.73 | 1.53 |

