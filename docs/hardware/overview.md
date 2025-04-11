---
id: overview
title: Hardware Overview
---

The ACE HPC Cluster is designed for bioinformatics and data-intensive research. Below are its key components.

### Compute Nodes
| Type         | Quantity | Cores | Memory   | Storage       |
|--------------|----------|-------|----------|---------------|
| Standard     | 13       | 208   |  416 GB  | 193.2 TB      |

## Specifications
Each of the nodes is a PowerEdge C620p a high-density, 2U rack server designed for scale out hyperscale environments. It is part of Dell's PowerEdge C-Series optimized for compute intensive workloads like HPC, virtualization, cloud computing and big data analytics.

### CPU

| Property                | Value                                 |
|-------------------------|----------------------------------------|
| Architecture            | x86_64                                 |
| CPU op-mode(s)          | 32-bit, 64-bit                         |
| Address sizes           | 46 bits physical, 48 bits virtual     |
| Byte Order              | Little Endian                         |
| CPU(s)                  | 16                                    |
| On-line CPU(s) list     | 0-15                                  |
| Vendor ID               | GenuineIntel                          |
| Model name              | Intel(R) Xeon(R) CPU E5-2680 0 @ 2.70GHz |
| CPU family              | 6                                     |
| Model                   | 45                                    |
| Thread(s) per core      | 1                                     |
| Core(s) per socket      | 8                                     |
| Socket(s)               | 2                                     |
| Stepping                | 7                                     |

**Note:** Plans are underway to upgrade the cluster that shall x10 the current capacity. Once this is completed, this documentation shall be updated too.

## Interconnect
- 10 Gb/s NREN connection (RENU).

## Login Nodes
- 1 login node, with 64 cores and 16 GB RAM.

## Additional Details
- 200Mbps internet connection (RENU).

See [Storage](storage) for file system details.