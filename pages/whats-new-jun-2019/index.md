# What's New - Jun 2019
<!-- date: 2019-06-26 08:00:00 -->

This month we released Bludit v3.9.1 and 3.9.2 with many bug fixes and improvements on the core; Bludit v3.9.2 is really stable and ready for production environments, we recommend update to this latest version.

Also, we provide Bludit PRO v3.9.2 for [Patreon collaborators](https://www.patreon.com/bludit), the idea of Bludit PRO is to get some support from the users who really enjoy Bludit. Bludit PRO come with the plugins [TimeMachineX](https://plugins.bludit.com/plugin/timemachine-x) and [Domain Migrator](https://plugins.bludit.com/plugin/domain-migrator) and some minor improves in the plugin `simple stats`.

## Raspberry PI project
This month we have a new project by [Jereme Hancock](https://jereme.dev) running Bludit in a Raspberry PI cluster, with a ton of plugins and different examples.

Take a look at his blog.
- https://pilab.dev/

## Docker image
We provide the official Bludit Docker image with the latest version of Bludit.

```
$ docker run --name bludit -p 8000:80 -d bludit/docker:3.9.2
```

More information at Docker Hub
- https://hub.docker.com/r/bludit/docker