---
id: storage
title: Storage Systems
---

The ACE HPC Cluster provides multiple storage options for users.

### File Systems
| Name      | Path          | Size   | Quota       | Purpose              |
|-----------|---------------|--------|-------------|----------------------|
| Home      | `/home/$USER` | 500 TB | 50 GB/user  | Personal files       |
| Scratch   | `/scratch`    | 2 PB   | None        | Temporary job data   |
| Project   | `/project`    | 1 PB   | By request  | Group storage        |

### Policies
- **Home**: Backed up daily; not for large datasets.
- **Scratch**: No backups; files older than 90 days are purged.
- **Project**: Requires approval; contact [support](#).

### Usage Tips
- Use Scratch for large, temporary files during jobs.
- Transfer completed data to Home or Project for safekeeping.