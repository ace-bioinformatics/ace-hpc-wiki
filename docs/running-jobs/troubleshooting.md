
---

### `docs/running-jobs/troubleshooting.md`
```markdown
---
id: troubleshooting
title: Troubleshooting Jobs
---

Common issues and solutions:

### Job Won’t Start
- Check queue: `squeue -u $USER`
- Resource limits exceeded? Adjust `--mem` or `--time`.

### Job Fails
- Review `.err` file for errors.
- Missing module? Load it in the script.

### Still Stuck?
- Contact [support](#) with job ID and error details.