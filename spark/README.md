# spark data transformation tool #

## build singularity container

```
singularity build spark.img Singularity
```

```
singularity build spark2.img Singularity2
```

## usage ##

See `pipeline.md`

 * input format: csv with header

 * output format: json or csv sparse format

   * the json format: each line is a json object 

     * simple object `col` 

     * compound object `table`, `instance_num`, `modifier_cd`, `col`


