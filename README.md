Docker Alpine openrc
====================

This Dockerfile can build containers capable to use openrc.

Branches
--------

This repository has multiple branches that relate to Alpine versions.

|Branch |Alpine Version|Docker image tag|
|-------|--------------|----------------|
|master |latest        |latest          |
|edge   |edge          |edge            |

Pull strategy
-------------

The different branches are **not** merged, they live as individual branches.

Manually starting
-----------------

```
docker run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:ro \
  robertdebock/alpine
```
