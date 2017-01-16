# Docker image for Latex environment with common packages

A Latex environment with common Latex packages and tools.

## Requirements

- Docker

## Setup

    docker pull ugrawert/latex

## Run

    docker run --rm -i -v $PWD:/data ugrawert/latex my_document.tex
