debug-perl
====

debug-perl is for debugging perl.

Command
----

```
# pull
docker pull doiken208/debug-perl
# run
docker run --name perl --cap-add=SYS_PTRACE --security-opt="seccomp=unconfined" -it doiken208/debug-perl
# if you want specific perl version, build it by build-arg
docker build --build-arg version=5.28.2 .
```
