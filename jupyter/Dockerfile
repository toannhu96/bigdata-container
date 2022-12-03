ARG OWNER=jupyter
ARG BASE_CONTAINER=$OWNER/pyspark-notebook
FROM $BASE_CONTAINER

LABEL maintainer="Jupyter Project <jupyter@googlegroups.com>"

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

# Install Tensorflow
RUN pip install tensorflow