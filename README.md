## Docker scripts

    docker build . -t igormcsouza/fer-challenge
    docker run --rm -it -p 8888:8888 -v ${PWD}:/workdir igormcsouza/fer-challenge:latest