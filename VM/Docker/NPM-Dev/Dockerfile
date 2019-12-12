FROM mhart/alpine-node:latest
COPY entrypoint.sh /entrypoint.sh

ENV PROJECT_DIR='/workdir'
ENV SCRIPT_NAME='dev'

ENTRYPOINT [ "/bin/sh" ]
CMD [ "/entrypoint.sh" ]