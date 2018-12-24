# MalariaGEN DataLab - User Image

This repo defines the default user image and environment for use with
MalariaGEN DataLab, which is a JupyterHub system deployed via
Kubernetes.

It is designed to be compatible with
[repo2docker](repo2docker.readthedocs.io). I.e., it should be possible
to use `repo2docker` to build a Docker image from this repository.

Note that continuous integration has been set up for this repository
via [Circle CI](https://circleci.com/gh/malariagen/datalab-image),
which will automatically build a Docker image each time the master
branch is updated, and will push the image to DockerHub. The image is
currently named
[cggh/malariagen-datalab](https://cloud.docker.com/u/cggh/repository/docker/cggh/malariagen-datalab). Continuous
integration was set up as described in the [repo2docker
docs](https://repo2docker.readthedocs.io/en/latest/howto/deploy.html).

To test the image on mybinder.org, click the image below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/malariagen/datalab-image/master?filepath=hello.ipynb)
