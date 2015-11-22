docker-opencv
=============
This docker image contains OpenCV 2.4.11.

To get started, pull the image from the dockerhub:

    sudo docker pull bunn/docker-opencv

or build it yourself:

    git clone git@github.com:mypetyak/docker-opencv.git
    cd docker-opencv
    sudo docker build .

Then open a bash shell inside a new container:

    sudo docker run -i -t bunn/docker-opencv bash
