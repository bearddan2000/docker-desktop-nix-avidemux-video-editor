# docker-desktop-nix-avidemux-video-editor

## Description
A POC for nix package manager loading avidemux video editor.

This is a barebones installation no pluggins where added.

In order to be able to get files out of the container one must add a volume to the docker run command.

ie. without a volume docker run --rm ... with a volume docker run --rm -v $(pwd):/app ...

## Tech stack
- nix
- avidemux

## Docker stack
- ubuntu:22.04

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
