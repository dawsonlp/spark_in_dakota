# spark_in_dakota
Try to tune spark configuration using Sandia labs Dakota

## [Dakota](https://dakota.sandia.gov/)
Dakota needs several inputs.
- an input .in file which is documented [here](https://dakota.sandia.gov/sites/default/files/docs/6.8/html-ref/input_spec.html). This defines the optimization algorithms that Dakota will use to search the parameter space.
- An executable script that takes a parameter file as input and writes to standard out
- A parameter file to use as an example/template. The fields can be specified to Dakota by position
- A driver script, which can be a python2.7 file that the Dakota UI can generate using a wizard
- An example output file, or specification of the fields that are under analysis

## [Spark](http://spark.apache.org)

