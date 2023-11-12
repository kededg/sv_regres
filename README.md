## Simple Regress example

### Description

TODO

### Build

For truing examples use Docker:

**Install:** [*Docker Install*](https://docs.docker.com/engine/install/ubuntu/)

**Build:** ```> docker build -f "Dockerfile" -t tag:v0 "."```

### Run 

Tap from **main** folder

```> docker run --rm -v $PWD:/work -w /work ked:v0 bash -c 'cd work/run && regrress.py test_list' ```