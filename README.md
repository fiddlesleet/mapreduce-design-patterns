# mapreduce-design-patterns
Hadoop ecosystem recipes for common data transformations &amp; iterative algorithms

### As with RDBMS, MapReduce deals with <key, multiValue> pairs, i.e. tuples of data. 

### As in Dplyr in R, the basic data transformation operations are: 
* Filter
* Sort (done via the shuffle stage)
* Aggregate (count, sum, average, etc.)
* Remap / Rename / Re-order
* Intersect (join)
* Group By (done in reducer, once like keys have been grouped via the Shuffle step) 
