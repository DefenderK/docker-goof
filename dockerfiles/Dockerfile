FROM ghost:2.37.2 as ghost

FROM node:10.4.0 as node

# Copy manifest files
COPY --from=ghost /var/lib/ghost /var/lib/ghost


LABEL org.opencontainers.image.source="https://github.com/a1doll/docker-goof"
LABEL io.snyk.containers.image.dockerfile="/dockerfiles/Dockerfile"
RUN ls
