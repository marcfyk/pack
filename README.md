# vim-packages

Packages to be loaded by vim 8 package feature.

1. Clone this repository in `.vim` with directory name `pack`. The `.vim` directory should have a structure `.vim/pack/{repository-files}`
2. Run `git submodule init`
3. Run `git submodule update`

### Adding packages

1. Run `git submodule add <remote_url> <destination-path>`
2. Commit changes

### Updating packages

1. Run `git submodule update`

### Deleting packages

1. Delete relevant lines in `.gitmodules`
2. Delete relevant lines in `.git/config`
3. Run `git rm --cached <path-to-submodule>`
4. Commit changes

