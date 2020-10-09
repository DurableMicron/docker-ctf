# Part 4 

This is a simple scenario based question

## Scenario
You have gained access to a comprimised ci cd tool, and have also gained knowledge
of the dockerfile and buildscript that will be run in order to transfer an extremely secret
value into a docker container. 

You also know that if you attempt to use the image they create as a base image it will
trigger their security system, but other docker commands are fine to run. You also have access 
to the console that the image itself will be built in.

### tldr restrictions
* can't build another container after `./run.sh` is executed.
