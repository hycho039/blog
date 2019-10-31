---
layout: post
title:  cancer vaccine docker environment developing ... 
date:   2019-09-26
categories: system biology  
---

ongoing ... 

testing the docker document to build image 

I forgot how to set up tools in ubuntu.. let me try first in the ubuntu docker image ... 

The ubuntu doesn't have anything including wget, sudo ... 

$ apt-get install update && apt-get install -y

$ apt-get install sudo 

$ apt-get install wget -y

$ apt-get install unzip 

$ wget https://www.bioinformatics.babraham.ac.uk/projects/fastqc/fastqc_v0.11.8.zip

$ unzip fastqc

$ cd fastqc 

$ chmod 755 fastqc

$ wget -O jre-8.0.111-linux-x64.tar.gz http://javadl.oracle.com/webapps/download/AutoDL?BundleId=216424

$ tar -zxvf jre-8.0.111-linux-x64.tar.gz

$ sudo ln -s /path/to/FastQC/fastqc /usr/local/bin/fastqc


Trying with bioconda... installing in the empty ubuntu looking difficult.

$ apt-get update && apt-get -yq dist-upgrade

$ apt-get install --yes wget
$ apt-get install sudo 

$ wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
$ sh Miniconda3-latest-Linux-x86_64.sh

$ wget http://www.bioinformatics.babraham.ac.uk/projects/fastqc/fastqc_v0.11.5.zip
$ apt-get install unzip 

$ apt-get update 
$ apt-get install unzip 
$ unzip fastqc_v0.11.5.zip

