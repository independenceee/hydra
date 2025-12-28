--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-28 04:56:23.49931268 UTC |
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
| 1| 5834 | 10.38 | 3.29 | 0.51 |
| 2| 6035 | 12.46 | 3.94 | 0.54 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7650 | 28.92 | 9.11 | 0.79 |
| 43| 14286 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10076 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 171 | 751 | 43.88 | 12.56 | 0.63 |
| 4 | 227 | 858 | 48.45 | 14.07 | 0.68 |
| 5 | 284 | 969 | 61.33 | 17.53 | 0.81 |
| 6 | 338 | 1085 | 73.35 | 20.79 | 0.94 |
| 7 | 393 | 1192 | 81.46 | 23.08 | 1.03 |
| 8 | 449 | 1303 | 94.13 | 26.66 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 23.92 | 7.60 | 0.48 |
| 2| 1946 | 25.88 | 8.79 | 0.51 |
| 3| 2129 | 28.34 | 10.15 | 0.55 |
| 5| 2434 | 31.88 | 12.49 | 0.61 |
| 10| 3166 | 40.69 | 18.27 | 0.75 |
| 40| 7527 | 96.88 | 53.90 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.77 | 7.36 | 0.42 |
| 2| 760 | 23.58 | 8.23 | 0.43 |
| 3| 941 | 26.63 | 9.78 | 0.48 |
| 5| 1249 | 30.68 | 12.24 | 0.54 |
| 10| 2037 | 39.76 | 18.09 | 0.69 |
| 42| 6696 | 98.68 | 55.81 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.42 | 8.68 | 0.47 |
| 2| 829 | 31.66 | 10.29 | 0.52 |
| 3| 1015 | 31.61 | 10.96 | 0.53 |
| 5| 1252 | 35.12 | 13.27 | 0.58 |
| 10| 2020 | 48.27 | 20.31 | 0.78 |
| 35| 5611 | 97.96 | 50.77 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 33.79 | 10.15 | 0.53 |
| 2| 879 | 36.56 | 11.60 | 0.57 |
| 3| 896 | 37.24 | 12.41 | 0.58 |
| 5| 1273 | 42.64 | 15.28 | 0.66 |
| 10| 1985 | 54.17 | 21.83 | 0.83 |
| 29| 5035 | 99.65 | 47.21 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 27.16 | 9.11 | 0.69 |
| 2| 5961 | 35.99 | 12.08 | 0.79 |
| 3| 6179 | 45.73 | 15.45 | 0.90 |
| 4| 6304 | 56.29 | 19.01 | 1.02 |
| 5| 6443 | 65.03 | 21.93 | 1.12 |
| 6| 6422 | 68.19 | 22.87 | 1.15 |
| 7| 6614 | 80.62 | 27.09 | 1.29 |
| 8| 6782 | 90.82 | 30.55 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1139 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 39 | 2219 | 7158 | 98.49 | 37.73 | 1.53 |

