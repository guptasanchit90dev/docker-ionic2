# Docker-Ionic2

Original source : https://github.com/bekkere/docker-ionic2

## Installation

Pull the image:

```console
docker pull guptasanchit90dev/docker-ionic2
```
Create a alias for simple execution: 

```console
alias ionic="docker run -ti --rm -p 8100:8100 -p 35729:35729 -v \$PWD:/myApp:rw guptasanchit90dev/docker-ionic2:latest ionic"

```

## Usage

Run the container using:

```console
ionic start MyApp --v2
ionic serve --lab -b # http://localhost:8100/ionic-lab
```
