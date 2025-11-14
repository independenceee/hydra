--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-14 04:33:49.329522082 UTC |
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
| 1| 5836 | 10.47 | 3.32 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 169 | 747 | 40.07 | 11.67 | 0.59 |
| 4 | 226 | 862 | 49.37 | 14.27 | 0.69 |
| 5 | 282 | 974 | 62.40 | 17.75 | 0.83 |
| 6 | 336 | 1081 | 69.75 | 20.01 | 0.91 |
| 7 | 394 | 1192 | 84.29 | 23.81 | 1.06 |
| 8 | 448 | 1303 | 83.04 | 24.00 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1822 | 24.00 | 7.62 | 0.48 |
| 2| 1966 | 26.50 | 8.99 | 0.52 |
| 3| 2143 | 28.02 | 10.07 | 0.54 |
| 5| 2409 | 30.92 | 12.22 | 0.59 |
| 10| 3196 | 42.13 | 18.68 | 0.77 |
| 40| 7594 | 97.83 | 54.17 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.57 | 7.32 | 0.41 |
| 2| 810 | 25.56 | 8.81 | 0.46 |
| 3| 922 | 25.10 | 9.32 | 0.46 |
| 5| 1168 | 28.39 | 11.61 | 0.51 |
| 10| 2018 | 40.68 | 18.36 | 0.70 |
| 42| 6787 | 98.59 | 55.80 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.54 | 8.47 | 0.46 |
| 2| 770 | 28.51 | 9.39 | 0.48 |
| 3| 932 | 32.72 | 11.23 | 0.54 |
| 5| 1221 | 36.56 | 13.64 | 0.60 |
| 10| 2073 | 48.08 | 20.24 | 0.78 |
| 36| 5957 | 97.80 | 51.58 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 33.87 | 10.16 | 0.53 |
| 2| 815 | 35.92 | 11.40 | 0.56 |
| 3| 992 | 38.63 | 12.83 | 0.60 |
| 5| 1247 | 42.61 | 15.27 | 0.66 |
| 10| 2032 | 53.91 | 21.77 | 0.83 |
| 29| 4893 | 97.71 | 46.65 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5794 | 27.13 | 9.09 | 0.69 |
| 2| 5981 | 37.01 | 12.50 | 0.80 |
| 3| 6041 | 43.90 | 14.73 | 0.88 |
| 4| 6280 | 54.89 | 18.50 | 1.00 |
| 5| 6324 | 59.05 | 19.79 | 1.05 |
| 6| 6739 | 78.26 | 26.49 | 1.27 |
| 7| 6645 | 79.47 | 26.75 | 1.28 |
| 8| 6864 | 93.40 | 31.42 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 37.74 | 13.85 | 0.83 |
| 10 | 37 | 2104 | 7090 | 94.39 | 36.12 | 1.49 |

