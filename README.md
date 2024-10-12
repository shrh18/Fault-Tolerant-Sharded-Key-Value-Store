# Fault-Tolerant-Sharded-Key-Value-Store

•	Built a fault-tolerant key-value store using the Raft consensus algorithm, with 2 Phase Lock-Commit transactions for data consistency.
•	Integrated advanced features such as persistence, minimal transfer sharding, optimistic concurrency control, and value versioning to enhance data replication, system reliability, and performance.
•	Incorporated would-wait-die protocols for deadlock prevention and optimized cross-shard transactions, reducing transaction conflicts by 40% and improving overall system throughput by 25%.

## This Project was pushed into private repository created by Prof. Shuai Mu (http://mpaxos.com/) at Stony Brook Univeristy. With the repo being private, it cannot be forked or viewed. Please email me and the Professor for Access (Strictly for viewing purposes). Attached are the screenshots of the original private repo for reference. Thank you.

<img width="960" alt="image" src="https://github.com/user-attachments/assets/3962f0c9-0dd7-4b06-9dd0-8350c1c8f242">

<img width="960" alt="image" src="https://github.com/user-attachments/assets/bc509c6a-bec8-4ace-b643-d324fe6ce7e9">

<img width="960" alt="image" src="https://github.com/user-attachments/assets/350b5a0d-246a-4619-82fc-92dd42ff2452">

<img width="960" alt="image" src="https://github.com/user-attachments/assets/dacf1137-f8fd-4ac4-abed-552533d2e455">


#  Distributed Systems Labs in C++

MIT 6.824 style distributed systems lab rebuilt in C++.
It includes a series of labs in which you will build a transactional, sharded, fault-tolerant key/value storage system (like Google Spanner, MongoDB, etc). 

## Lab assignments

- Lab 1 - Replicated State Machine 
- Lab 2 - Fault-tolerant Key-value Store
- Lab 3 - Sharded Key-value Store
- Lab 4 - Distributed Transactions

## Lab environment

A modern linux environment (e.g., Ubuntu 22.04) is recommended for the labs. If you do not have access to this, consider using a virtual machine. 

## Getting started (Ubuntu 22.04)

Get source code:
```
git clone --recursive [repo_address]
```

Install dependencies:
```
sudo apt-get update
sudo apt-get install -y \
    git \
    pkg-config \
    build-essential \
    clang \
    libapr1-dev libaprutil1-dev \
    libboost-all-dev \
    libyaml-cpp-dev \
    libjemalloc-dev \
    python3-dev \
    python3-pip \
    python3-wheel \
    python3-setuptools \
    libgoogle-perftools-dev
sudo pip3 install -r requirements.txt
```

For next steps, checkout the guidelines in the [course web page](http://mpaxos.com/teaching/ds/22fa/labs.html).

## Author and acknowledgements
Author: Shuai Mu, Julie Lee (lab 1)

Many of the lab structure and the guideline text are taken from MIT 6.824. The code is based on the acedemic prototypes of previous research works including Rococo/Janus/Snow/DRP/Rolis/DepFast.
