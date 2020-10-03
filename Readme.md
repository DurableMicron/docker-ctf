# Docker CTF - WIP
This repo contains a series of simple docker ctf challenges that scale in difficulty. 

For each part the goal is to a find the flags that are in the format `flag-xxx`.

## How to run?
- Requires docker with buildkit enabled. (May work without but I was using buildkit).
- For each part there are 4 files.  


| file | description |
| ----- | ------ |
`Dockerfile` |The dockerfile used to build the image
|`./run.sh` | A command that builds and runs the docker image, you may need to inspect this to see the command arguments used. 
|`solution.md` | Overview of the solution

Note: The provided files are used as examples but you should be able to solve all of these without the direct use of these files. In other words just copypasting values from the `Dockerfile`, `./run.sh` etc does not count as solving the challenge. In future versions the provided dockerfiles would be practice and then a real image would be uploaded to dockerhub. 

You are allowed to run docker commands before and after run.sh, but you cannot modify the existing files themselves.
