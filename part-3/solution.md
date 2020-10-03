# Part 3 Solution

By looking at the run command we can see that it is injected via an env variable rather than a a build arg, this means that it is unavailable in docker history. 

Since the container also exits immediately we also cannot `docker exec` into it, however we can insepct it. 

Using `docker container ls -a` we can find the id of the stopped container. 

then using `docker inspect` we can view some info, including the env vars which contain our flag.

