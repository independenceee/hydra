--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-10 04:13:37.968513354 UTC |
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
| 1| 5837 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6242 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.72 | 5.91 | 0.64 |
| 10| 7647 | 28.81 | 9.07 | 0.78 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 170 | 747 | 43.80 | 12.53 | 0.63 |
| 4 | 225 | 858 | 49.51 | 14.33 | 0.69 |
| 5 | 281 | 969 | 60.69 | 17.37 | 0.81 |
| 6 | 337 | 1081 | 73.23 | 20.80 | 0.94 |
| 7 | 393 | 1196 | 85.04 | 24.12 | 1.06 |
| 8 | 448 | 1303 | 83.41 | 24.10 | 1.06 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1817 | 23.92 | 7.60 | 0.48 |
| 2| 1955 | 25.39 | 8.68 | 0.50 |
| 3| 2126 | 27.86 | 10.03 | 0.54 |
| 5| 2389 | 30.89 | 12.21 | 0.59 |
| 10| 3170 | 41.54 | 18.50 | 0.76 |
| 40| 7511 | 96.18 | 53.67 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 747 | 24.27 | 8.46 | 0.44 |
| 3| 907 | 25.02 | 9.30 | 0.46 |
| 5| 1167 | 28.03 | 11.48 | 0.51 |
| 10| 1798 | 35.54 | 16.91 | 0.64 |
| 40| 6665 | 99.98 | 54.88 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 26.83 | 8.26 | 0.45 |
| 2| 766 | 28.47 | 9.38 | 0.48 |
| 3| 910 | 30.23 | 10.54 | 0.51 |
| 5| 1215 | 34.26 | 13.02 | 0.57 |
| 10| 2064 | 47.95 | 20.21 | 0.77 |
| 35| 5770 | 95.22 | 50.14 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 805 | 35.85 | 11.38 | 0.56 |
| 3| 955 | 37.95 | 12.63 | 0.59 |
| 5| 1209 | 41.93 | 15.06 | 0.65 |
| 10| 2010 | 54.21 | 21.85 | 0.83 |
| 30| 5030 | 99.43 | 47.76 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.57 | 0.64 |
| 2| 6023 | 36.93 | 12.44 | 0.80 |
| 3| 6073 | 44.84 | 15.05 | 0.89 |
| 4| 6263 | 55.01 | 18.53 | 1.00 |
| 5| 6339 | 60.12 | 20.24 | 1.06 |
| 6| 6520 | 70.35 | 23.72 | 1.18 |
| 7| 6720 | 83.15 | 28.16 | 1.32 |
| 8| 6866 | 93.10 | 31.35 | 1.43 |
| 9| 7023 | 95.55 | 32.15 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 284 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1136 | 6510 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1709 | 6856 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2221 | 7161 | 99.38 | 38.04 | 1.54 |

