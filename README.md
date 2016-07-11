# dev-install

Installs all the stuff.

**NOTE**: This is alpha, and probably doesn't work, yet.

## Instructions

### Remove other Ruby Version Managers, first!

```
rvm-implode
rm -rf ~/.rbenv
```

### Install Apple Xcode command line tools

```
xcode-select --install
```

Then, restart your computer.

### Setup your development environment

```
git clone git@github.com:radavis/dev-install.git
cd dev-install
./bin/install
```

### Check that everything went OK.

```
./bin/check
```

### Fix permissions on the home directory

If the script bails out, it is likely that the permissions are screwed up.

```
./bin/permissions
```

## Check your dev environment without cloning the repo.

This is useful if you have installed via [`rocket_fuel`](https://github.com/LaunchAcademy/rocket_fuel) or via Launch Academy's instructions in [Ignition](http://blog.launchacademy.com/ignition-interactive-pre-learning-on-steroids/)

```
curl https://raw.githubusercontent.com/radavis/dev-install/master/bin/check | bash
```
