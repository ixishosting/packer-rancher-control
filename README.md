# Packer Rancher Control

Packer scripts to generate AMI images for running Rancher on AWS EC2.

# Building AMI Images

To generate an AMI image for a Rancher server execute the following command;

```
packer build server.json
```

To generate an AMI image for a Rancher node execute the following command;

```
packer build node.json
```
