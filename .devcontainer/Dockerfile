# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.158.0/containers/alpine/.devcontainer/base.Dockerfile

# [Choice] Node.JS version
# default version
ARG VARIANT="14.15.5"
#FROM mcr.microsoft.com/vscode/devcontainers/base:0-alpine-${VARIANT}
FROM node:${VARIANT}-alpine

# ** [Optional] Uncomment this section to install additional packages. **
# RUN apk update \
#     && apk add --no-cache <your-package-list-here>
RUN apk --no-cache add git