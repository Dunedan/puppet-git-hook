# Overview

This project contains a git hook, which is meant to be used for git repositories
containing puppet configuration and helps to ensure proper syntax and style for
puppet manifests and templates.

The hook can be either used as ```pre-commit``` hook in a working copy or as
```update``` hook in a bare repository.

# Usage

* Ensure you've the following binaries available on your system:
    * ```puppet```
    * ```puppet-lint``` (>= 1.0.0)
    * ```ruby```
    * ```erb```
* Store the ```pre-commit``` script either named as ```pre-commit``` in the
  hooks directory of you working copy or store it named as ```update```
  (```update.secondary``` for gitolite)  in the hooks directory of a bare
  repository. Ensure that the hook has executable permissions.

# Contribution

Pull Requests are welcome!
