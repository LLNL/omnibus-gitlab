The latest docker guide can be found here: [GitLab Docker images](/doc/docker/README.md).

# Local build

To avoid downloading a prebuilt `.deb` file from Gitlab
([and instead substitute your own](https://docs.gitlab.com/omnibus/build/prepare-build-environment.html)),
do:

```
# Copy your deb file into this directory as gitlab.deb
cp /path/to/your/custom/gitlab.deb gitlab.deb

# Run docker build
docker build -t custom-omnibus-gitlab .
```

