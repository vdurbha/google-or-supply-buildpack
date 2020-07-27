# Introduction 
This is a supply buildpack to be used to include the Google OR buildpack. This buildpack will not work as a finalize buildpack. We have to use the Java buildpack as the finalize buildpack to make this work.

# Getting Started
The purpose of this supply buildpack is to supply the Google OR native library to those Java applications that require it at runtime to run optimization algorithms

# Usage
cf push -b google-or-suppy-buildpack -b java-buildpack