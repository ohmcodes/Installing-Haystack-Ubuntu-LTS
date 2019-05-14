# Installing-Haystack-Ubuntu-LTS


#### There was a bug in the OP's version of virtualenv, as described [here](https://github.com/pypa/virtualenv/issues/463). The problem was fixed by running:
	pip install --upgrade virtualenv		pip install --upgrade virtualenv



 ===> Currently Haystack supports 1.x and 2.x

 Download ElasticSearch: https://www.elastic.co/downloads/past-releases/elasticsearch-2-4-6
- Can download tar, zip..

 Install ElasticSearch
	1. mkdir ~/<main folder for elasticsearch>
	2. cd ~/<main folder for elasticsearch>
	3. tar -xzvf elasticsearch-2.4.6.tar.gz
	4. cd elasticsearch-2.4.6 
	5. bin/elasticsearch

 # If error shows up: "could not find java; set JAVA_HOME or ensure java is in PATH"
Ubuntu Solution-
	1. sudo add-apt-repository ppa:webupd8team/java
	2. sudo apt-get update
	3. sudo apt-get install oracle-java8-installer

 Run: bin/elasticsearch

 Installing Haystack
	pip install django-haystack 

 For adding elasticsearch to python path
	pip install "elasticsearch>=2.0.0,<3.0.0"  # for Elasticsearch 2.x
