| Option | Purpose                               | What it does                                             | If Not Used                                     |
| ------ | ------------------------------------- | -------------------------------------------------------- | ----------------------------------------------- |
| `-l`   | List                                  | Lists all installed packages                             | You won’t see installed packages                |
| `-Rs`  | Search                                | Search **available** (repo) packages by name             | You can’t find packages to install              |
| `-s`   | Search local (installed) pkgs by name | You won’t see if something is already installed          |                                                 |
| `-i`   | Info                                  | Show details about a package (version, desc, deps, etc.) | You only see name, not detailed info            |
| `-f`   | Files                                 | List files owned by a package                            | You don’t know what a package installed         |
| `-o`   | Owner                                 | Find which package owns a file                           | You can’t tell which package a file belongs to  |
| `-x`   | Dependencies                          | Show all required dependencies of a package              | You won’t know what it needs to work            |
| `-X`   | Reverse deps                          | Show what packages depend on it                          | You don’t know what will break if you remove it |
| `-R`   | Remote                                | Query from repo instead of local system                  | Will only show installed info otherwise         |
| `-m`   | Manual install                        | Show packages manually installed (not pulled as deps)    | Useful for identifying orphans                  |
