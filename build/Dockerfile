FROM docker:latest

LABEL "name"="OpenFaaS Build Action"
LABEL "maintainer"="Lucas Roesler <roesler.lucas@gmail.com>"
LABEL "version"="1.0.0"

LABEL "com.github.actions.name"="GitHub Action for OpenFaaS Function Image Build"
LABEL "com.github.actions.description"="Wraps the OpenFaaS CLI to enable the faas-cli build command."
LABEL "com.github.actions.icon"="package"
LABEL "com.github.actions.color"="blue"

RUN apk add --no-cache \
		git \
        ca-certificates

COPY --from=openfaas/faas-cli:0.9.2 /usr/bin/faas-cli /usr/bin/
