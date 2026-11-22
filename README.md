# Hello Flask in Docker

A tiny Flask web app containerized with Docker.

## What it does
Serves a single page at `/` with a hello message.

## Build
docker build -t hello-flask .

## Run
docker run --rm -p 5000:5000 hello-flask

Open http://localhost:5000

## What I learned
- Writing a Dockerfile for a Python app
- Installing dependencies in an image
- Mapping container ports to the host
- Running and cleaning up containers
