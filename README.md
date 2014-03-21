docker-npm-lazy-mirror
======================

Simple container to setup a npm-lazy-mirror

Please see https://www.npmjs.org/package/npm-lazy-mirror for more information

Example usage:

```
docker run -name npm-lazy-mirror -d -p 2000:2000 -v /home/npm/:/tmp/npm-lazy/ dkuffner/npm-lazy-mirror npm-lazy-mirror --cache-dir /tmp/npm -b 0.0.0.0 -a my-npm-mirror-hostname
```

