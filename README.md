[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/aaalex-off_github.svg)](https://hub.docker.com/r/rubygem/aaalex-off_github/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/aaalex-off_github.svg)](https://hub.docker.com/r/rubygem/aaalex-off_github/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/aaalex-off_github.svg)](https://hub.docker.com/r/rubygem/aaalex-off_github/)
[![Gem Downloads](https://img.shields.io/gem/dt/aaalex-off_github.svg)](https://rubygems.org/gems/aaalex-off_github/)
# aaalex-off_github

Auto-Generated Docker image for aaalex-off_github to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/aaalex-off_github`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/aaalex-off_github`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/aaalex-off_github`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/aaalex-off_github/)
