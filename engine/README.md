# Flutter Engine

## `gclient` bootstrap

Flutter engine uses `gclient` to manage dependencies.

If you've already cloned the flutter repository:

1. Copy one of the `engine/scripts/*.gclient` to the root folder as `.gclient`:
    1. Googlers: copy `rbe.gclient` to enable faster builds with [RBE](https://github.com/flutter/flutter/blob/master/engine/src/flutter/docs/rbe/rbe.md)
    2. Everyone else: copy `standard.gclient`
2. run `gclient sync`
