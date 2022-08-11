# hive-docker

This repository contains a single submodule, the [ethereum/hive](https://github.com/ethereum/hive) repository.

DockerHub builds branches of this repository prefixed with docker_, and then the built image can be used by erigon CI to run hive. The main branch when pushed will trigger a dockerhub build, producing an image with the `latest` tag.