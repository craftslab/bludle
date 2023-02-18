# bludle

[![Build Status](https://github.com/craftslab/bludle/workflows/ci/badge.svg?branch=main&event=push)](https://github.com/craftslab/bludle/actions?query=workflow%3Aci)
[![codecov](https://codecov.io/gh/craftslab/bludle/branch/main/graph/badge.svg?token=YCXTOSU3WR)](https://codecov.io/gh/craftslab/bludle)
[![Go Report Card](https://goreportcard.com/badge/github.com/craftslab/bludle)](https://goreportcard.com/report/github.com/craftslab/bludle)
[![License](https://img.shields.io/github/license/craftslab/bludle.svg)](https://github.com/craftslab/bludle/blob/main/LICENSE)
[![Tag](https://img.shields.io/github/tag/craftslab/bludle.svg)](https://github.com/craftslab/bludle/tags)



## Introduction

*bludle* is the tool to build Blueprint from Gradle written in Go.



## Prerequisites

- Go >= 1.18.0



## Run

```bash
version=latest make build
./bin/bludle --config-file="$PWD"/config/config.yml
```



## Docker

```bash
version=latest make docker
docker run -v "$PWD"/config:/tmp ghcr.io/craftslab/bludle:latest --config-file=/tmp/config.yml
```



## Usage

```
```



## Settings

*bludle* parameters can be set in the directory [config](https://github.com/craftslab/bludle/blob/main/config).

An example of configuration in [config.yml](https://github.com/craftslab/bludle/blob/main/config/config.yml):

```yaml
```



## License

Project License can be found [here](LICENSE).



## Reference
