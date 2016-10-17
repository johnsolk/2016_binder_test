# 2016_binder_test

To create a Docker container of this repo (uses [Kubernetes](http://kubernetes.io/)), go to [mybinder](http://mybinder.org) and paste the url of this repo. (Make sure to use the github url, not the clone address.)

https://github.com/ljcohen/2016_binder_test

This will build a binder instance:

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/ljcohen/2016_binder_test)

Since a Docker image is created for this repo, this link can be given to people to all run an identical copy of the repo. The repo may contain data files, which people can then interact with using Jupyter notebooks. New Jupyter notebooks can be started. Alternatively, an existing Jupyter notebook (index.ipynb) can be included within the repo, which will start when someone launches the binder instance. files Additional packages can be installed using the terminal found within the binder.
