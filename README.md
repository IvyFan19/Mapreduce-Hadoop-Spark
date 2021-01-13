# Mapreduce-Hadoop-Spark

## Goal
Recognize anagrams and palindromes using Apache Hadoop and Apache Spark on Google Cloud.

## Input Dataset
Enron Email dataset:  https://www.cs.cmu.edu/~./enron/enron_mail_20150507.tar.gz 

## Outputs
- Sets of word anagrams, where each set contains all the words that are made of the same set of letters. For example, one set could be (anemic, cinema, iceman).
-  A list of all the palindromes (for example, madam or racecar) used in the above Email dataset.

## Summary

### What is Hadoop and why we use it?
Hadoop is an open source framework that is used to efficiently store and process large datasets. Instead of using one large computer to store and process the data, Hadoop allows clustering multiple computers to analyze massive datasets in parallel more quickly. 

### Apache Spark VS Apache Hadoop

|     Category for Comparison    |     Apache Hadoop                                    |     Apache Spark                                                         |
|--------------------------------|------------------------------------------------------|--------------------------------------------------------------------------|
|     Hardware                   |     Disk (read and write)                            |     RAM (caching and processing data)                                    |
|     Speed                      |     100X times than MapReduce                        |     Faster than traditional system                                       |
|     Cost                       |     Open-source platform +      Low-cost hardware    |     Open-source platform +     High-cost memory running computation      |
|     Data Processing            |     Batch / real-time / iterative/ graph             |     Batch                                                                |
|     Ease of Use                |     Java or Python                                   |     Java, Scala, R, Python,   Spark SQL                                  |
|     Fault Tolerance            |     High (Replicate data across the servers)         |     High (Track RDD block creation process, then   rebuild a dataset)    |