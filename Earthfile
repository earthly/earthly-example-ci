VERSION 0.7
PROJECT earthly-technologies/earthly-example-ci-project

FROM alpine:3.17

hello-world-pipeline:
    PIPELINE
    TRIGGER push main
    TRIGGER pr main
    BUILD +hello-world

hello-world:
    RUN echo Hello world
