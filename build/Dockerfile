FROM docker:latest

RUN apk add --no-cache \
		git \
        ca-certificates

COPY --from=openfaas/faas-cli:0.9.1 /usr/bin/faas-cli /usr/bin/
