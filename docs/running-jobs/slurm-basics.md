
---

### `docs/running-jobs/slurm-basics.md`
```markdown
---
id: slurm-basics
title: SLURM Basics
---

The ACEBDIS HPC Cluster uses SLURM to manage job scheduling.

### Key Commands
- Submit a job: `sbatch script.sh`
- Check queue: `squeue -u $USER`
- Cancel a job: `scancel <job_id>`
- Job info: `scontrol show job <job_id>`

### Partitions
| Name    | Max Time | Nodes | Purpose         |
|---------|----------|-------|-----------------|
| batch   | 7 days   | 20    | General use     |
| gpu     | 3 days   | 4     | GPU jobs        |

See [Job Scripts](job-scripts) for examples.