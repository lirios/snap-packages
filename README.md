## Liri Snap Packages

Snap packages for Liri core apps, cross-platform apps and shell.

### Dependencies

* [Ubuntu](https://www.ubuntu.com/) == 16.04
* [snapcraft](https://snapcraft.io)

### Build

It is recommended to build inside a clean lxc container with Ubuntu 16.04.

From the root each app directory, run:
```sh
snapcraft
```

### Update plugins

To update the snapcraft [plugins](https://github.com/lirios/snapcraft-plugins) submodules, run:
```
git submodule foreach git pull origin develop
git add -A
git commit
```
