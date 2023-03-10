# our base image
FROM alpine:3.17

# install python and pip
RUN apk add --update py3-pip

# copy files required for the app to run (in same directory as Dockerfile, otherwise use full path)
COPY app.py /usr/src/app/

# run the application (runs some software inside the container)
CMD python3 /usr/src/app/app.py

# ENTRYPOINT (used for things that are run every time the container is started, like a server)

