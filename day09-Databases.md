<!--- Copyright (C) 2024 teslazonda --->

<!--- This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. --->

<!--- This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details. --->

<!--- You should have received a copy of the GNU General Public License along with this program.  If not, see https://www.gnu.org/licenses/ --->

# Day 9 Notes

## Dynamo DB

* NoSQL Database
* Scales to massive workloads, "serverless"
* Millions of requests per seconds, 100s TB storage.
* Low-latency

### DAX
* DynamoDB accelerator.
* Fully Managed in-memory cache for DynamoDB.
* 10x performance improvement.

### Global Tables
* Make a DynamoDB table accessible with low latency in multiple regions.

## Redshift
* Redshift is based on PostgreSQL, but not used for Online Transactions, it is used for Online analytical processing (data warehousing).
* Columnar storage.
* Pay as you go.
* Integrated with BI.

## Amazon EMR
* Elastic MapReduce.
* Creates Hadoop clusters (Big Data).
* hundreds of EC2 instances.
* Apache Spark, HBase, Presto, FLink.
* EMR provisions and configures.
* Use cases: data processing, machine learning, big data...

## Amazon Athena
* Serverless query service to perform analytics against S3 objects.
* SQL language to query the files.
* Pricing $5 per TB stored on S3
* Use case for business intelligence, analytics, reporting.
* Serverless, S3, SQL Athena.

## Amazon QuickSight
* Make dashboards for databases.

## DocumentDB
* Aurora is an AWS version of MongoDB (NoSQL).
* JSON data

## Amazon Neptune
* Graph database
* Example: Social network.

## Amazon Timestream
* Serverless time series database.
* Example: stock market data.

## Amazon QLDB
* Records financial transactions.
* Quantum Ledger Database.
* Immutable system. Review all history of all the changes made to your application data overtime.

## Amazon Managed Blockchains
* Execute transactions without central authority.
* Ethereum

## AWS GLUE
* Managed extract, transform, and load (ETL) service.
* Serverless.

## DMS - Database Migration Service
* Supports Migrations from source DBs to Databases in AWS.