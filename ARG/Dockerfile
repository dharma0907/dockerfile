ARG version
FROM almalinux:${version-9}
ARG cource=devops \
    topic=docker \
    author=dharma 
# HOW TO SET ARG VALUES TO ENV TO GET ACCEESS INSIDE THE CONTAINER, JUSR CALL ENV AND SET VALUES OF ARG TO ENV
env COURCE=${cource} \
    TOPIC=${topic} \
    AUTHOR=${author}

RUN echo "cource: ${cource} topic: ${topic} author: ${author}"