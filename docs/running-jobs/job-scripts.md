---
id: job-scripts
title: Writing Job Scripts
---

Here’s an example SLURM job script for a bioinformatics task.

### Example: BLAST Job
```bash
#!/bin/bash
#SBATCH --job-name=blast_job
#SBATCH --output=blast_job.out
#SBATCH --error=blast_job.err
#SBATCH --time=12:00:00
#SBATCH --nodes=1
#SBATCH --ntasks-per-node=8
#SBATCH --mem=32gb

module load blast/2.12.0
blastn -query input.fasta -db database -out results.txt -num_threads 8
```

### Tips
Match `--ntasks-per-node` to CPU-intensive tasks.