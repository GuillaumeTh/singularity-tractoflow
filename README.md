Singularity related files for Human-NF
--------------------------------------

The image for singularity can be built using _singularity_human.def_ with the command:
```singularity build image_name.img singularity_human.def.def```.

It can be used to run the Human-NF pipeline with the option
```-with-singularity image_name.img``` of nextflow.

To build the singularity, please run the command from the directory ```singularity-human```.
Otherwise, ```scilpy.tar``` is not found.
 