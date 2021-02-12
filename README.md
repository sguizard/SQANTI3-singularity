# SQANTI3-singularity
A definition file for building SQANTI3 singularity container (adapted from [joelnitta/sqanti3-docker](https://github.com/joelnitta/sqanti3-docker))

## Building container
`sudo singularity build sqanti3_1.6.{sif, def}`

## Using SQANTI3
There are two main Python scripts in SQANTI3: sqanti3_qc.py and sqanti3_RulesFilter.py. 
They can be run in the image as follows:

[sqanti3_qc.py](https://github.com/ConesaLab/SQANTI3#running-sqanti3-quality-control-script)
```
singularity exec sqanti3_1.6.sif sqanti3_qc.py -h
```

[sqanti3_RulesFilter.py](https://github.com/ConesaLab/SQANTI3#filtering-isoforms-using-sqanti3-output-and-a-pre-defined-rules)
```
singularity exec sqanti3_1.6.sif sqanti3_RulesFilter.py -h
```

