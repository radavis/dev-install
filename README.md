# dev-install

Installs all the stuff.

__NOTE:__ This is alpha, and probably doesn't work, yet.

## Remove other Ruby Version Managers, first!

```
rvm-implode
rm -rf ~/.rbenv
```

## Install Apple Xcode command line tools

```
xcode-select --install
```

Then, restart your computer.

## Install your Ruby development environment

```
./dev_install
```

## Fix permissions on the home directory

If the script bails out, it is likely that the permissions are screwed up.

```
./fix_permissions
```
