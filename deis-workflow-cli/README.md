# Deis Workflow CLI snap

This project creates a working snap for Deis Workflow CLI.
Deis is an interesting free PaaS with Kubernetes. The 2.0 version of the
client has just been released, with not packaging at sight.

## Current state

Working features:
 - The snap builds, needs to test in a real server.

Known issues:
 - Without devmode, it gets stuck.
   Reported in https://bugs.launchpad.net/snappy/+bug/1590221

Unknowns:
 - Many features not tested.
