# asp_stereo_docker
NASA Ames Stereo Pipeline (ASP) tool set docker file

#prerequisite
docker installed

# build command
docker pull milijan/asp-stereo

# starting a new shell
docker run -it -t -e DISPLAY --env=QT_X11_NO_MITSHM=1 -v /tmp/.X11-unix:/tmp/.X11-unix:rw -i milijan/asp-stereo /bin/bash
