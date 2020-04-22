# Node App Packer

## Node

This is a packer uses the berksfile to adds the node app cookbook provisions and creates an AMI from those provisions


### Pre-requisites

- Packer
- git

## Packer
Packer is an open source tool for creating identical machine images for multiple platforms from a single source configuration. Packer is lightweight, runs on every major operating system, and is highly performant, creating machine images for multiple platforms in parallel.

### To validate if there is no errors with the packer.json file.

```
packer validate packer.json
```
### To build AMI

```
packer build packer.json
```
