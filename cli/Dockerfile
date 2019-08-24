FROM openfaas/faas-cli:0.9.2

LABEL "name"="OpenFaaS CLI Action"
LABEL "maintainer"="Lucas Roesler <roesler.lucas@gmail.com>"
LABEL "version"="1.0.0"

LABEL "com.github.actions.name"="GitHub Action for OpenFaaS"
LABEL "com.github.actions.description"="Wraps the OpenFaaS CLI to enable faas-cli commands."
LABEL "com.github.actions.icon"="package"
LABEL "com.github.actions.color"="blue"

COPY entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
