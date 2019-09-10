# charts-mirror-images
[![Build Status](http://drone.cnrancher.cn/api/badges/guangbochen/charts-image-mirros/status.svg)](http://drone.cnrancher.cn/guangbochen/charts-image-mirros)

This repo sync [rancher/charts](https://github.com/rancher/charts) images to the [ranchercharts](https://cloud.docker.com/u/ranchercharts) repo in the Docker Hub.

## how it works
add image.txt file to the ./mirror-images folder with the following pattern and the Drone CI will auto sync the images.
```
drone/drone ranchercharts/drone-drone 1.2
```
