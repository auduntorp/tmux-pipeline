# tmux pipeline 
Execute build script when receiving git changes, and e-mail authors on errors.

## installation
Use hooks to enable pipeline based on tmux when you push to a git server:
```shell
cp hooks/post-receive ~/path/to/git/repo/.git/hooks
cp checkout_and_build.sh ~/path/to/git/repo/
```
Then edit the build pipeline script.
