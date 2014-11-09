currently only works with the fork of ProcessJSONInstaller: `https://github.com/owzim/ProcessJSONInstaller`

install the fork from your processwire installation directory:

```sh
$ cd site/modules
$ git clone https://github.com/owzim/ProcessJSONInstaller
```

install the module from the `Modules` Page

grab the JSON files from this repo:

```sh
$ cd site
$ git clone https://github.com/processwire-recipes/json-installer-modules
```

in admin go to `Setup > JSON Installer`

A tab named `PWR` should be there, install `ProcessWire Recipes` which will install all the JSON sub modules

ATTENTION: currently some ASMSelects are not assigned properly after first installation, so install it twice (fix on the way)