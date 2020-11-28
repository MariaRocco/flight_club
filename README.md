# flight_club

[![Build Status](https://travis-ci.com/drc56/flight_club.svg?branch=master)](https://travis-ci.com/drc56/flight_club) [![Coverage Status](https://coveralls.io/repos/github/drc56/flight_club/badge.svg?branch=master)](https://coveralls.io/github/drc56/flight_club?branch=master)

# Running in container
## System dependencies
1. `docker`
2. `docker-compose`

## Running Locally
1. Run:
```
docker-compose up dev
```
2. In a browser navigate to:
```
0.0.0.0:5000
```
Congrats you are now running the flight club app


## Running Tests
1. Run:
```
docker-compose build test
docker-compose up test
```
2. Review results in `results.xml` file
