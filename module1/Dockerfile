# syntax = docker/dockerfile:1.0-experimental
ARG FROM
# hadolint ignore=DL3006
FROM ${FROM}

SHELL ["/bin/ash", "-eo", "pipefail", "-c"]

COPY maven/ /app
