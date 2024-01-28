To run Vesta, unzip 3rd and run:

> ./build.sh

Script FLTrust.sh contains performance experiments for Verifiable FLTrust while FoolsGold.sh contains performance experiments for Verifiable FoolsGold

To run the program on arbitrary inputs execute:

> ./main {log number of clients} {log model size} {range proof protocol} {number of threads} {operation}

* {range proof protocol}: 1 -> lookup based, 2-> optimized bit-decomposition, 3-> naive sumcheck based range proof
* {operation} : 1 -> Run FLTrust, 2-> Run FoolsGold, 3-> Test range proof
