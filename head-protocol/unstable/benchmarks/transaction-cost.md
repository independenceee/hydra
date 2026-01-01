--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-01 04:59:02.498569975 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6041 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 29.47 | 9.30 | 0.79 |
| 43| 14285 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 171 | 747 | 42.84 | 12.35 | 0.62 |
| 4 | 225 | 858 | 51.05 | 14.67 | 0.71 |
| 5 | 284 | 969 | 64.58 | 18.31 | 0.85 |
| 6 | 338 | 1081 | 65.84 | 19.14 | 0.87 |
| 7 | 395 | 1192 | 85.92 | 24.23 | 1.07 |
| 8 | 452 | 1307 | 80.06 | 23.14 | 1.02 |
| 9 | 505 | 1418 | 96.51 | 27.63 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1821 | 24.29 | 7.69 | 0.48 |
| 2| 1880 | 24.40 | 8.40 | 0.49 |
| 3| 2144 | 28.39 | 10.16 | 0.55 |
| 5| 2346 | 30.45 | 12.07 | 0.59 |
| 10| 3230 | 43.44 | 19.04 | 0.78 |
| 40| 7667 | 99.70 | 54.64 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.54 | 7.30 | 0.41 |
| 2| 768 | 23.56 | 8.22 | 0.43 |
| 3| 952 | 26.56 | 9.77 | 0.48 |
| 5| 1179 | 28.39 | 11.58 | 0.52 |
| 10| 2082 | 42.05 | 18.75 | 0.72 |
| 42| 6717 | 99.36 | 56.01 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 661 | 29.17 | 8.91 | 0.48 |
| 2| 785 | 30.91 | 10.06 | 0.51 |
| 3| 974 | 30.98 | 10.76 | 0.52 |
| 5| 1191 | 36.42 | 13.59 | 0.59 |
| 10| 2112 | 45.34 | 19.51 | 0.75 |
| 34| 5721 | 94.18 | 49.20 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 33.87 | 10.16 | 0.53 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 895 | 37.13 | 12.38 | 0.58 |
| 5| 1298 | 42.72 | 15.30 | 0.66 |
| 10| 2109 | 55.37 | 22.21 | 0.85 |
| 30| 4844 | 98.69 | 47.49 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5801 | 27.09 | 9.08 | 0.69 |
| 2| 5866 | 32.61 | 10.89 | 0.75 |
| 3| 6037 | 41.62 | 13.95 | 0.85 |
| 4| 6245 | 53.75 | 18.07 | 0.99 |
| 5| 6385 | 60.54 | 20.32 | 1.07 |
| 6| 6627 | 74.94 | 25.33 | 1.23 |
| 7| 6597 | 78.69 | 26.45 | 1.27 |
| 8| 6797 | 87.47 | 29.34 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1139 | 6513 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1709 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2221 | 7160 | 97.61 | 37.43 | 1.52 |

