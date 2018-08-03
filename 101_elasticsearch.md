# Elasticsearch 101 - Elasticsearch

## Description
> Elasticsearch is a distributed, RESTful search and analytics engine capable of solving a growing number of use cases. As the heart of the Elastic Stack, it centrally stores your data so you can discover the expected and uncover the unexpected. -the Elasticsearch [website](https://www.elastic.co/products/elasticsearch)

Simply put, Elasticsearch can be used to store huge (or small) amounts of (often semi-structured or even unstructured) data, while still ensuring that data can be retreived easily and quickly. 

## Installation
Elasticsearch download link: https://www.elastic.co/downloads/elasticsearch  
Elasticsearch Docker image download link: https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html

## Configuration
How Elasticsearch gets deployed is heavily dependent on your specific use case. Following the installation instructions should leave you with an Elasticsearch cluster you can store data in.

> Note: For development use, you probably want to use the Docker image.

## Usage
Remember, Elasticsearch is simply a place to store data, how you get data inside and out of Elasticsearch is your choice.

It's mosty likely that you will use a programming language like Python or Go to write data to Elasticsearch . For Go and Python there both an official and non-official clients available. Most of these clients will enable you to both read data from and write data to Elasticsearch .

### Kibana
If you simply want to search or have a peek at what is inside of an Elasticsearch cluster, you can use Kibana.

## Test

Use curl to get a valid response from a running Elasticsearch Docker container.

Try to use a python module to connect to an official Elasticsearch container and write some data to it.

```
   Copyright 2018 Opensource Academy

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```
