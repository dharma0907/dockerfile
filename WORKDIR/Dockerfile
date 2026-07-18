FROM almalinux:9
RUN cd /tmp
# cd won't work in docker, if we run this it won't move top /tmp.
 RUN mkdir /app
WORKDIR /app
RUN echo "Present directory: ${PWD}"