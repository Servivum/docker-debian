![Debian Jessie](https://img.shields.io/badge/Debian-Jessie-brightgreen.svg?style=flat-square) 
![License MIT](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square) 
[![Travis](https://img.shields.io/travis/Servivum/docker-debian.svg?style=flat-square)](https://travis-ci.org/Servivum/docker-debian?style=flat-square)
[![ImageLayers Size](https://img.shields.io/imagelayers/image-size/servivum/debian/latest.svg?style=flat-square)](https://imagelayers.io/?images=servivum/debian:latest)

# Debian Docker Base Image with Useful Tools

Dockerfile for extending official Debian image with useful tools, e.g. Git, Wget, etc.

## What's inside?

- ca-certificates: Brings root certs for trusting secured connections with common CAs. 
- cron: Use Cron jobs for scheduling tasks like cleanup processes.
- curl: Swiss army knife to use various number of protocols.
- git: THE version control system.
- nano: Easy editor for modifying files.
- openssh-server: For connecting to the container via SSH and executing commands within.
- ssmtp: Tiny mail server for sending mails from your application to the world. 
- supervisor: Helper for running multiple processes in a container, e.g. cron and openssh-server.
- unzip: Unpack ZIP archives.
- vim: Powerful editor for nerds.
- wget: The standard for downloading archives.