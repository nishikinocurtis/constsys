# Basic Register/Cache/Mem/Disk Ops

- CPU access register <1ns.
- One cpu cycle <1ns.

- L1 cache access 4-5 cycles, approx. 1ns.

- L2 cache access 10-20 cycles, <10ns.
- Expensive CPU instruction, 10-20 cycles.
- Wrong branch prediction penalty, <10ns

- L3 cache access 20-40 cycles, 10-15ns.

- Main memory access, local NUMA node, 70-100ns.

- Memcpy, 64KB, local NUMA node, <10us.

- Sequential memory read, 1MB, local NUMA node, 50us. 

- Sequential memory read, 1GB, local NUMA node, <100ms.

- Latency, Local NUMA DRAM Read v.s. Cross NUMA DRAM Read, 2Socket, UPI @ 11.2GT/s, Xeon Gold IceLake, 77ns vs 130ns

- Throughput, Local NUMA DRAM Read v.s. Cross NUMA DRAM Read, 2Socket, UPI @ 11.2GT/s, Xeon Gold IceLake, 177GBps vs 55GBps
