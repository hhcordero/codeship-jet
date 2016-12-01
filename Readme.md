# Jet for Codeship, in a docker container

Just `docker pull egeland/codeship-jet` the image, then put a file like this into your PATH:

```
exec docker run --rm -it -v "$PWD:/root" egeland/codeship-jet:latest $*
```

## Repo

https://github.com/egeland/codeship-jet

Pull requests welcome :)

