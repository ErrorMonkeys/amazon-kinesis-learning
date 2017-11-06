# Learning Amazon Kinesis Development

The master branch provides completed code for the [Learning Kinesis Development][learning-kinesis] series in the [Kinesis Developer Guide][kinesis-developer-guide].

Each learning module in the series has its own branch (for example, learning-module-1 branch for the first learning module). If you are interested in following the learning plan for this series, it is recommended that you start with the code in the corresponding module branch to stay in sync with each learning module.

[learning-kinesis]: http://docs.aws.amazon.com/kinesis/latest/dev/learning-kinesis.html
[kinesis-developer-guide]: http://docs.aws.amazon.com/kinesis/latest/dev/introduction.html

# About this fork
This fork includes the relevant pom file compatible with Version 1.0.
This also includes a new branch named "using-kinesis-producer-library" which demonstrates using the Amazon Kinesis Producer Library (KPL) instead of the Amazon Kinesis Client Library in StockTradesWriter.java. The Maven POM file is also updated to include the KPL and its own dependencies.
