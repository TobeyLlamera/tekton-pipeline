FROM golang

COPY . /go/src/github.com/TobeyLlamera/tekton-pipeline/

RUN go install github.com/TobeyLlamera/tekton-pipeline/test/gohelloworld

ENTRYPOINT /go/bin/gohelloworld

# Document that the service listens on port 8080.
EXPOSE 8080
