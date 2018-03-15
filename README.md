# Build R with rJava Docker Image

[![Docker Build Status](https://img.shields.io/docker/build/mangothecat/buildr-java.svg)](https://hub.docker.com/r/mangothecat/buildr-java/)

An image, based on the `mangothecat/buildr` image based on the `rocker/r-ver` base image, with a few system dependencies installed. Most noteably openjdk-8-jdk (R >= 3.3.0 on Debian stretch), or jdk 7 (R 3.2.X Debian Jessie)

The following R packages are pre-installed:

* `rJava`
* `remotes`

It also installs pandoc so you can do RMarkdown things without needing all of RStudio.

The intended useage is a base image for building R packages that have a Java dependency.
