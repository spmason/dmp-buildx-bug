Reproduction of docker-maven-plugin bug with submodules and dockerfiles

```
[INFO] DOCKER> WARNING: No output specified for docker-container driver. Build result will only remain in the build cache. To push result image into registry use --push or to load image into docker use --load
[INFO] DOCKER> WARNING: local cache import at ......./dmp-buildx-bug/module1/target/docker/dmp-buildx-bug/cache not found due to err: could not read ....../dmp-buildx-bug/module1/target/docker/dmp-buildx-bug/cache/index.json: open ....../dmp-buildx-bug/module1/target/docker/dmp-buildx-bug/cache/index.json: no such file or directory
[INFO] DOCKER> error: failed to solve: failed to read dockerfile: open /tmp/buildkit-mount3293280157/Dockerfile: no such file or directory
[INFO] DOCKER> docker --config ....../dmp-buildx-bug/module1/target/docker/dmp-buildx-bug/docker buildx rm dmp_dmp-buildx-bug
```