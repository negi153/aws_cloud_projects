# AWS Cloud Automations
This repository contains the projects/automations to consume the static as well as realtime data and load into datawarehosue after transformation.
- Designed, Develop, Deployed the ETL pipeline from scratch.
- Bug-fixes, Enhancement, unit testing and documentation
- Deployed the infrastructure using Cloudformation service IAAC (Infrastructure as a code)

## Realtime GPS data processing
The goal of this project is to consume the vehicles GPS data in realtime and load into S3 bucket and Snowflake datawarehouse after applying transformations.

![realtime-data-processing](https://github.com/negi153/aws_cloud_projects/assets/27079205/b4ef9380-b09e-4755-8474-8de6b5a9ad83)

## S3 Data Processing
The goal is to process the incremental data from S3 bucket and load into Snowflake Datawarehouse after applying transformations.

![S3-data-processsing](https://github.com/negi153/aws_cloud_projects/assets/27079205/dbfaab55-3d74-415a-8694-ff5463a107b0)

## Customer geographical data ingestion
The goal is to consume incremental Customer geographical data from S3 and load into oracle table after aplying the transformaiton in Glue job.

![geo-codes](https://github.com/negi153/aws_cloud_projects/assets/27079205/8d4a6d9d-8660-4a7a-ac13-aa0d08cc68c1)

