**WARNING**: **This is NOT the official docker-rust-nightly repository!**

**The official repository is at https://github.com/rust-lang/docker-rust-nightly.**

---

This repository serves the purpose of having some nightly builds "from the past",
frozen in time. If you know of a better way to achieve this please let us know!

The images for the "frozen" nightly builds can be found on
[Docker Hub](https://hub.docker.com/repository/docker/initc3/rust-frozen).

This image has three types of tags:

* `<YYYY.MM.DD>-buster`
* `<YYYY.MM.DD>-slim-buster`
* `<YYYY.MM.DD>-alpine3.10`

matching the nightly build corresponding to `<YYYY.MM.DD>`.

## Supported tags and respective Dockerfile links
* [2019.11.21-buster](https://github.com/initc3/docker-rust-frozen/blob/master/2019.11.21/buster/Dockerfile)
* [2019.11.21-slim-buster](https://github.com/initc3/docker-rust-frozen/blob/master/2019.11.21/buster/slim/Dockerfile)
* [2019.11.21-alpine3.10](https://github.com/initc3/docker-rust-frozen/blob/master/2019.11.21/alpine3.10/Dockerfile)
