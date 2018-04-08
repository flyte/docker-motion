Docker Motion
=============

Builds the latest motion code from the github repository.

Usage
-----

Output example config file:

```bash
docker run -ti --rm flyte/motion config
```

Run motion:

```bash
docker run -ti --rm -v /path/to/motion.conf:/etc/motion/motion.conf:ro flyte/motion
```
