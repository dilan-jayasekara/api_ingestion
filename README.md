# api_ingestion

There are three main resources we need to create


1. Lambda Function

Reads from a google sheet (and api I developed using AppScript) and convert it to a pandas dataframe and output as a csv file on S3

2. Event Bridge Rule

Added a daily event bridge rule (to run everyday at 4am)

3. S3 Bucket

S3 bucket is declared as an env variable on the cloud formation template
