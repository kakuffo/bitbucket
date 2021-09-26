# Bitbucket Pipelines

## Basic configuration

With a basic configuration, you can do employ many functionalities in your Bitbucket pipeline.  You can for example
write scripts to build and deploy your projects and configure caches to speed up builds. 
You can also specify different images for each step to manage different dependencies across actions you are performing in your pipeline.
A pipeline is made up of a list of steps, and you can define multiple pipelines in the configuration file. 
In the following diagram provided below, you can see a pipeline configured under the default section. 
The pipeline configuration file can have multiple sections identified by particular keywords.
The purpose of this project is to make available Bitbucket pipeline code snippets which I have used on my journey as
a software engineer, and the code snippits are organised into two folders; Testing and DevOps.
Within these roles I have found myself employing many techniques to aid in my daily activities.

### Testing
The testing folder contains snippts which I employed for realising continuos integration ( CI )