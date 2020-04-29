ARG base_repo
FROM ${base_repo}r-base:latest
LABEL docker image with embedded R model

COPY *.zip /pybox/model

ENTRYPOINT ["/bin/bash", "startServer.sh"]


