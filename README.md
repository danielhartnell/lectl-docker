# lectl Docker container

## Summary

A Docker container which provides and runs the lectl command. I was having some
trouble running `lectl` on my Mac so I created this as a temporary workaround.
When time permits, I will see if I can identify the actual problem and submit a
PR to the [lectl project](https://github.com/sahsanu/lectl) to support Mac OS X.

## Usage

```
$ docker build -t lectl .
$ docker run lectl <insert_domain>
```

You can also pull it from Docker Hub:

```
$ docker run dhartnell/lectl-docker <domain>
```
