[//]: # (-*- markdown -*-)

[![](https://travis-ci.org/mbodenhamer/docker-debian-python.svg?branch=master)](https://travis-ci.org/mbodenhamer/docker-debian-python)

A Debian Python 2 base image with [depman](https://github.com/mbodenhamer/depman) and [yatr](https://github.com/mbodenhamer/yatr).

## Usage

To launch a container inside a Python session, run:

    $ docker run --rm -it -v `pwd`:/app mbodenhamer/debian-python:latest


A container can also be launched with Python arguments, like so:

    $ docker run --rm -it -v `pwd`:/app mbodenhamer/debian-python:latest python --version