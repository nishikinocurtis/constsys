# Slower IO

- Read an 8K page from SSD, 100us.
- Write to SSD, near 1ms.

- Sequential Read 1GB, SSD, x100 ms.
    - i.e., SSD Seq Read BW = <10 GB/s, without RAID.

- RTT, intra-zone cloud server, x100us.

- RTT, intra-region data center, 5ms.

- HDD seek time, 5ms

- Trans N.A. continental, trans Atlantic RTT, x10ms.

- U.S. West to Singapore RTT, x100 ms.

- Transfer 1GB data, inter AZ, assuming 10Gbps+ BW, approx 1s.
