# beam-datalake
A new IO connector named DataLakeIO, which support to connect Apache Beam and data lake, such as Delta Lake, Apache Hudi, Apache iceberg.
## Requirements
* Apache Spark 3.2.0 is required. 
* Apache Beam 2.41.0 is required.
## Quickstart
1. First, use maven to compile and install this project.  
2. If you use Delta Lake, please refer to [beam-delta-example](<https://github.com/nanhu-lab/beam-delta-example>),  which shows how to use Apahe Beam to write data to Delta Lake, and how to use Apache Beam to read data from Delta Lake.  
3. If you use Apache Iceberg, please refer to [beam-iceberg-example](<https://github.com/nanhu-lab/beam-iceberg-example>),  which shows how to use Apahe Beam to write data to Apache Iceberg, and how to use Apache Beam to read data from Apache Iceberg.  
4. If you use Apache Hudi, please refer to [beam-hudi-example](<https://github.com/nanhu-lab/beam-hudi-example>),  which shows how to use Apahe Beam to write data to Apache Hudi, and how to use Apache Beam to read data from Apache Hudi.  
