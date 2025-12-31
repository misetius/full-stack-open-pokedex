# Python as a language for CI/CD pipeline

For this exercise we are looking at python as a language for making CI/CD pipeline. 

## Linting, testing and building with Python

For checking that code has been programmed in right style tool called pylint could be used. This tools helps to find mistakes and lines that break coding standards. With file .pylintrc directories to ignore can be defined. 

For testing I would use pytest. This tool is feature rich and different kinds of tests such as unit tests and API tests can be written quite efficiently and with ease with this tool. 

With Python there is not really need for building. When using python requirements should still be defined in some file and installed in the pipeline. This assures that the tests and the linting can be run in the pipeline. 

## Alternatives for Jenkins and Github Actions

For pipelines there are lot of alternatives. For example pipelines could be constructed with Gitlab CI/CD, Azure DevOps Pipelines or CircleCI. All of these have free plans. With quick search I would still float towards Gitlab CI/CD or CircleCI because these seem to offer best free plans.

## Setting up the environment

For this project cloud based solution to create the pipeline would probably be the best idea. The reason for this is the fact that team of six people could be defined as small to medium sized software. Because of the size of the software special needs should be known to justify self-hosted environment.