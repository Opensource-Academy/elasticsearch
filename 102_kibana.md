# Elasticsearch 102 - Kibana

## Description
> Kibana lets you visualize your Elasticsearch data -Kibana homepage

Simply put, Kibana can be used to 'look' at the data indexed on an Elasticsearch cluster. Kibana can be used to search through data and to generate fancy graphical representations from data.

## Installation
Follow the instructions on https://www.elastic.co/downloads/kibana to install and configure Kibana.

## Configuration
Follow the instructions on the download page to properly configure Kiabana.

If you are using the Elasticsearch Docker image, remember to uncomment the username and password lines and fill in the correct credentials.

> Note: the Elasticsearch Docker image comes with the default username 'elastic' and password 'changeme'.

## Usage

### Kibana on the web
If you get access to an instance of Kibana that was already set up for you, you can read the entry on searching to get a basic understanding of how Kibana queries work.

### Local Kibana
If you want to run a local version of Kibana, you have to 'point' Kibana to the Elasticsearch cluster you want to connect to. This is done through the Kibana configuration file.

### Searching
http://lucene.apache.org/core/6_2_1/queryparser/org/apache/lucene/queryparser/classic/package-summary.html#package.description

## Pitfalls
While trying to connect Kibana to the official Elasticsearch docker image, you have yo use a username and password provided by the Elasticsearch docker page. Find out where the username and password are. Find out where to put them so Kibana can work with them.

## Test

Use Kibana to look at the data you put into Elasticsearch in the previous module. If you did not put information in Elasticsearch yet, do this first.

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
