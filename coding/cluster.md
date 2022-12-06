# User Guide for Cluster

- [User Guide for Cluster](#user-guide-for-cluster)
  - [Some useful commands for HPC](#some-useful-commands-for-hpc)
  - [SlURM](#slurm)
    - [submit a batch\_processing job](#submit-a-batch_processing-job)
    - [submit a interaction job](#submit-a-interaction-job)

## Some useful commands for HPC

- **look the quota of user**

``` bash
pgquota
```

- **look the information of all nodes**

```bash
sinfo
```

## SlURM

### submit a batch_processing job

- **submit**

``` bash
 sbatch run.sh
```

- **monitor the information**

``` bash
squeue -u p311104
```

``` bash
jobinfo
```

### submit a interaction job
