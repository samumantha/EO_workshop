
# CSC projects

* necessary for doing anything
* needs '**P**rinciple **I**nvestigator'
* PI applies for CSC project with
    * Billing units
    * services
  
Project members share resources, storage and computing storage


# my.csc.fi

[`my.csc.fi`](https://my.csc.fi)



# Example batch job script:

```bash

#!/bin/bash 
#SBATCH --job-name=myTest 
#SBATCH --account=<project> 
#SBATCH --time=02:00:00
#SBATCH --cpus-per-task=4 
#SBATCH --mem-per-cpu=2000 
#SBATCH --partition=small
 
module load geoconda

srun python my_python_script.py input output

```


# Billing Units (BU)

* per project
* resources (CPU / GPU amount and time) on supercomputer
* Virtual Machine uptime
* Allas storage amount and time

# Computing resources for you*

<p align="center">
  <img src="images/puhti_pouta2.png" width="50%">
</p>

# Matlab

Matlab parallel server (MPS)
* Matlab on own computer with own license
* parallel computing toolbox needed
* CSC has serverside toolbox

Limited also available on Puhti webinterface

# Storage and sharing solutions 


[`research.csc.fi/storage`](https://research.csc.fi/storage)
[`paituli.csc.fi/`](https://paituli.csc.fi/)

# Data on Puhti/Allas

* almost all Paituli data also on Puhti 
(Q: what open public datasets would be interesting to have?)
* Sentinel-2 over agricultural Finland, growing season public on Allas
* direct access to Allas without download with some tools