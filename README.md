# DLC-apptainer

The apptainer.def file contains the definition file to build an apptainer container for BEN to put on the DCCN High Performance Computer.

https://github.com/yu02019/BEN

To build the container:
```{bash}
apptainer build apptainer ben.sif apptainer.def
```

BEN does not yet exist as a module on the HPC

Currently maintained by @grandjeanlab. 

