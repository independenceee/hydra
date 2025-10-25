--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-25 04:15:33.78790965 UTC |
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
| 1| 5836 | 10.78 | 3.43 | 0.52 |
| 2| 6037 | 12.99 | 4.13 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14286 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 751 | 43.61 | 12.48 | 0.63 |
| 4 | 226 | 858 | 48.35 | 14.05 | 0.68 |
| 5 | 281 | 969 | 57.61 | 16.64 | 0.78 |
| 6 | 338 | 1081 | 69.34 | 19.87 | 0.90 |
| 7 | 395 | 1192 | 78.83 | 22.59 | 1.00 |
| 8 | 449 | 1303 | 87.03 | 24.86 | 1.09 |
| 9 | 504 | 1414 | 99.14 | 28.26 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1956 | 25.88 | 8.79 | 0.51 |
| 3| 2121 | 28.06 | 10.08 | 0.54 |
| 5| 2345 | 30.45 | 12.07 | 0.59 |
| 10| 3201 | 41.63 | 18.54 | 0.76 |
| 41| 7737 | 98.10 | 54.91 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 22.77 | 7.36 | 0.42 |
| 2| 755 | 23.65 | 8.24 | 0.43 |
| 3| 897 | 25.56 | 9.48 | 0.46 |
| 5| 1278 | 31.27 | 12.39 | 0.55 |
| 10| 2114 | 40.69 | 18.35 | 0.70 |
| 39| 6520 | 99.78 | 54.11 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 29.13 | 8.90 | 0.48 |
| 2| 834 | 29.22 | 9.61 | 0.49 |
| 3| 868 | 32.04 | 11.02 | 0.53 |
| 5| 1130 | 35.52 | 13.32 | 0.58 |
| 10| 2036 | 47.51 | 20.06 | 0.77 |
| 35| 5647 | 99.25 | 51.16 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.16 | 0.53 |
| 2| 834 | 35.81 | 11.37 | 0.56 |
| 3| 938 | 37.87 | 12.61 | 0.59 |
| 5| 1309 | 42.79 | 15.33 | 0.66 |
| 10| 2018 | 54.14 | 21.83 | 0.83 |
| 30| 5083 | 99.64 | 47.83 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5836 | 27.12 | 9.10 | 0.69 |
| 2| 5953 | 35.92 | 12.05 | 0.79 |
| 3| 6060 | 44.89 | 15.06 | 0.89 |
| 4| 6108 | 47.23 | 15.77 | 0.91 |
| 5| 6382 | 61.76 | 20.76 | 1.08 |
| 6| 6602 | 71.81 | 24.23 | 1.20 |
| 7| 6713 | 83.86 | 28.26 | 1.33 |
| 8| 6793 | 87.63 | 29.42 | 1.37 |
| 9| 6772 | 90.10 | 30.21 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 30 | 1709 | 6856 | 79.78 | 30.37 | 1.32 |
| 10 | 39 | 2219 | 7158 | 99.38 | 38.04 | 1.54 |

