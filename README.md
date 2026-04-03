A repo to save some custom void linux packages, which are not suitable for
upstream

Custom packages should be put in directory `my-pkgs`, call `start` when you prepare to
test custom packages, the shell will call `fuse-overlayfs` to mount custom
packages to `void-packages/srcpkgs` directory; call `end` when you want to commit, the
mounted file will be unmounted.
