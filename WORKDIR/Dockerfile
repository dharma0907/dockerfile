FROM almalinux:9
RUN cd /tmp
# cd won't work in docker, if we run this it won't move top /tmp.
RUN mkdir /app
WORKDIR /app
# we need to use WORKDIR especially in docker for creating and moving to directories.
RUN echo "Present directory: ${PWD}"
