# Run PROVEAN using PBS Pro.

Edit the `PROVEAN.sh` config file, then run:

```
qsub -J 1-N -v config=PROVEAN.sh -l select=1:ncpus=1:mem=4GB -l walltime=48:00:00 PROVEAN.pbs
```
