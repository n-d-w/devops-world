# devops-world

Dev(Who)Ops scripts

# Start

Start your new DevOps journey. Install bpkg and then install all your shell script using bash manager bpkg:

```sh
curl -sLo- https://get.bpkg.sh | bash
```

# Configure bpkg

Set `$BPKG_REMOTE` variable to path of your Github repo and create
[Wiki page](https://github.com/n-d-w/devops-world/wiki/index.md)

```
export BPKG_REMOTE=github.com/n-d-w/devops-world
# add list of your packages into index.md:
git clone github.com:n-d-w/devops-world.wiki.git
vim devops-world.wiki/index.md

```

# Install

Available as a [bpkg](http://www.bpkg.sh/)
```sh
bpkg install [-g] n-d-w/devops-world
```
