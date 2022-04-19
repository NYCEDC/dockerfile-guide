# Dockerfile Guide

This guide is a consortium of best practices to follow when writing Dockerfile files.

## Best Practices

* Use [official Docker images](https://github.com/docker-library/official-images)
* Run as [non-root user](https://docs.docker.com/engine/security/#linux-kernel-capabilities)
* Do not use `latest` tags
* Use `image` tags as git tags
* Use COPY (be specific when possible), not ADD
* Avoid installing unnecessary dependencies
* Each container should have only one responsibility

## Resources

* [Docker - Best practices for writing Dockerfiles](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/)
* [Docker - Intro Guide to Dockerfile Best Practices](https://www.docker.com/blog/intro-guide-to-dockerfile-best-practices/)
* [Hexops - Dockerfile best practices](https://github.com/hexops/dockerfile#dockerfile-best-practices)
