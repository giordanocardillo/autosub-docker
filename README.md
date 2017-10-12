[![Docker Stars](https://img.shields.io/docker/stars/giordanocardillo/autosub-docker.svg?style=flat-square)](https://hub.docker.com/r/giordanocardillo/autosub-docker/) [![Docker Pulls](https://img.shields.io/docker/pulls/giordanocardillo/autosub-docker.svg?style=flat-square)](https://hub.docker.com/r/giordanocardillo/autosub-docker/) [![Docker Automated build](https://img.shields.io/docker/automated/giordanocardillo/autosub-docker.svg?style=flat-square)](https://hub.docker.com/r/giordanocardillo/autosub-docker/)

# Autosub Docker

This is just a Docker port of the very good autosub Python utility by [agermanidis](https://github.com/agermanidis/autosub).


## How to use it

1. Download `autosub` file
2. Move it to `/usr/local/bin/autosub`
3. Make sure it is executable `chmod a+x /usr/local/bin/autosub`
4. Use it like you installed with `pip`

### In one line

```
curl --fail -L https://github.com/giordanocardillo/autosub-docker/releases/download/1.0/autosub > /usr/local/bin/autosub && chmod a+x /usr/local/bin/autosub
```

Autosub documentation is [here](https://github.com/agermanidis/autosub).

Thank you agermanidis!
