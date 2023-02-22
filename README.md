# asdf-gradle

[![Build Status](https://travis-ci.org/rfrancis/asdf-gradle.svg?branch=master)](https://travis-ci.org/rfrancis/asdf-gradle)

[gradle](https://gradle.org/) plugin for the [asdf](https://github.com/asdf-vm/asdf) version manager

## Install

```sh
asdf plugin-add gradle https://github.com/rfrancis/asdf-gradle.git
```

## Use

Check out the [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install and manage versions of other tools.

When installing Gradle using `asdf install` if you not wish to have it check the package signature for whatever reason, you can set `no` using `export GRADLE_SIGNATURE_CHECK=no` example:

```sh
export GRADLE_SIGNATURE_CHECK=no 
```

If you want to use a custom distribution url, for example in a corporate setting you can set this:

```sh
export GRADLE_DISTRIBUTION_URL=https://services.gradle.org/distributions
```

Observation:

* `GRADLE_SIGNATURE_CHECK` - `yes` (for yes, check the signature) is the default

NEEDED: Someone to take over maintenance of this plugin.
