# Geogebra-Javascript-Bundle
Provides Javascript codebase from the Geogebra projects

This repository takes the master branch of 
[the official Geogebra repository](https://github.com/geogebra/geogebra) and builds, via GitHub Actions, the Javascript codebase for the web version of Geogebra. 

The code here is generated using GWT starting from the Java codebase of Geogebra. The Geogebra codebase is made available under the  copyright detailed in the license [here](https://stage.geogebra.org/license). 

The goal of this repository is to provide extended building facilities for this application generating a Javascript codebase using GitHub Actions. Building will be possibly extended in future to provide a non obfuscated Javascript codebase for the Geogebra applet. 

The releases in this project are issued with the same tags used by the official Geogebra repository on Github. Each release from this repo contains a zip file. This file can be unzipped onto a webspace and will provide an instance of the Geogebra application. A similar bundle is also provided by the Geogebra Institute and therefore what is maintained here is just a personal experiments. 

This is part of a project comprising other two repositories whose goal is to collect a large number of Geogebra self evaluated, multilingual,  tests for high school Mathematics and Physics, to be used within Moodle.
