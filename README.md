## Install locally

```console
nix build
```

### Run the server
```console
result/bin/app
```

### Build with Docker
```console
docker build -t flask-example:dev .
```
Run server
```console
docker run --rm -p 8080:8080 flask-example:dev
```

### Delete local build
delete `result` folder, then 
```console
nix store delete
```

## References
##### Flask + Nix + Docker Example

This is the example repository to accompany my
[blog post on using Nix to build Docker images](https://mitchellh.com/writing/nix-with-dockerfiles).
