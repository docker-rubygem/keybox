[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/keybox.svg)](https://hub.docker.com/r/rubygem/keybox/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/keybox.svg)](https://hub.docker.com/r/rubygem/keybox/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/keybox.svg)](https://hub.docker.com/r/rubygem/keybox/)
[![Gem Downloads](https://img.shields.io/gem/dt/keybox.svg)](https://rubygems.org/gems/keybox/)
# keybox

Auto-Generated Docker image for keybox to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/keybox`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/keybox`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/keybox`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/keybox/)
