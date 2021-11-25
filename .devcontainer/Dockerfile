# Copyright (c) Jupyter Development Team.
# Distributed under the terms of the Modified BSD License.
ARG BASE_CONTAINER=jupyter/all-spark-notebook:spark-3.2.0
FROM $BASE_CONTAINER


USER root
# Allow passwordless sudo
RUN echo "jovyan ALL=(ALL) NOPASSWD:ALL" | tee /etc/sudoers.d/notebook

USER jovyan
