--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-17 04:15:57.161261495 UTC |
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
| 1| 5837 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 171 | 747 | 42.33 | 12.17 | 0.61 |
| 4 | 225 | 858 | 54.01 | 15.40 | 0.74 |
| 5 | 282 | 974 | 61.01 | 17.54 | 0.81 |
| 6 | 341 | 1081 | 73.20 | 20.76 | 0.94 |
| 7 | 395 | 1192 | 83.29 | 23.66 | 1.05 |
| 8 | 449 | 1303 | 93.48 | 26.45 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 23.92 | 7.60 | 0.48 |
| 2| 1947 | 25.55 | 8.72 | 0.51 |
| 3| 2074 | 26.91 | 9.76 | 0.53 |
| 5| 2357 | 31.42 | 12.34 | 0.60 |
| 10| 3243 | 43.45 | 19.06 | 0.78 |
| 40| 7453 | 93.64 | 53.00 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 630 | 22.84 | 7.38 | 0.42 |
| 2| 821 | 25.49 | 8.79 | 0.46 |
| 3| 909 | 25.10 | 9.32 | 0.46 |
| 5| 1245 | 30.15 | 12.07 | 0.54 |
| 10| 2159 | 43.70 | 19.19 | 0.74 |
| 43| 6852 | 98.78 | 56.52 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 27.50 | 8.46 | 0.46 |
| 2| 785 | 30.91 | 10.06 | 0.51 |
| 3| 943 | 30.90 | 10.74 | 0.52 |
| 5| 1262 | 35.00 | 13.24 | 0.58 |
| 10| 2173 | 46.43 | 19.84 | 0.76 |
| 36| 5860 | 95.35 | 50.85 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 704 | 33.83 | 10.15 | 0.53 |
| 2| 764 | 35.14 | 11.16 | 0.55 |
| 3| 949 | 37.84 | 12.60 | 0.59 |
| 5| 1200 | 41.97 | 15.07 | 0.65 |
| 10| 2187 | 55.26 | 22.18 | 0.85 |
| 29| 4987 | 98.76 | 46.90 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.57 | 0.64 |
| 2| 6000 | 36.89 | 12.43 | 0.80 |
| 3| 6090 | 44.54 | 14.99 | 0.89 |
| 4| 6253 | 54.97 | 18.53 | 1.00 |
| 5| 6493 | 66.00 | 22.28 | 1.13 |
| 6| 6437 | 71.19 | 23.84 | 1.18 |
| 7| 6759 | 80.98 | 27.33 | 1.30 |
| 8| 6910 | 92.91 | 31.26 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1140 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2165 | 7128 | 97.51 | 37.29 | 1.52 |

