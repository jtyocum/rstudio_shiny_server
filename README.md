# Shiny Server

This playbook is designed to bootstrap the deployment of an R Studio Shiny Server on Ubuntu 20.04. The playbook performs the following tasks:

* basic system hardening
* enables automatic updates
* sets timezone to America/Los_Angeles
* install of R, and Shiny Server
* install of Caddy (reverse proxy)

## Requirements

* fresh Ubuntu 20.04 amd64 install
* user with SSH key and sudo access

## Manual Tasks

This playbook doesn't fully configure Caddy as a reverse proxy. Please see the example config for ideas.
