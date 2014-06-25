# gitlib

A Git client library.

### Supported Commands
 * Git clone
 * Git commit
 * Git push
 * Git status
 * Git branch
 * Git checkout
 * Git fetch
 * Git revert

### Coming soon
 * Git pull
 * Git merge
 * Git stash
 * Git diff
 * Git treediff
 * submodule support

### Known issues
 * The library does not support repositories with submodules.
 * It is recommended to use the library for small / medium sized repos.
 * It is recommended to clone repository with `depth = 1`.
 * Only works with remote git repos that support the smart protocol over http or https.
 * Only supports basic authentication.
