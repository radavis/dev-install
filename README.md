# dev-install

Installs all the stuff.

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
./dev-install
```

## Fix permissions on the home directory

If the script bails out, it is likely that the permissions are screwed up.

```
./fix-permissions
```
