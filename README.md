# Implementation of Ant Colony Optimisation for the Travelling Salesman Problem

Implemeted using Golang

See main.go for more details

## To start
Just run `./main` on Linux or `main.exe` on Windows

## Other Details
The implementation only considers the ```DIMENSION``` and ```NODE_COORD_SECTION``` fields in the files given. It uses the former to get the total number of cities and the latter to get the coordinates of those cities

## Usage
(Assuming Go is installed and $GOPATH points to the proper directory...if not then refer [here](https://golang.org/doc/install) for installation and  [here](https://golang.org/doc/code.html) for post installation setup.)

Run `$ go get github.com/mtShaikh/tsp_through_aco` to get the files
>Run `$ go install` command in the directory where main.go file is (```$GOPATH/src/github.com/mtShaikh/main```):
and then run
`$ $GOPATH/bin/main`
