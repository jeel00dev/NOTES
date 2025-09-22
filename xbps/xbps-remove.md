| Option     | Meaning                                                      | What it does                                                  | What happens if you don’t use it                    |
| ---------- | ------------------------------------------------------------ | ------------------------------------------------------------- | --------------------------------------------------- |
| `-R`       | Recursive                                                    | Removes dependencies that are no longer used (auto-installed) | Leaves orphan packages installed                    |
| `-o`       | Remove orphans                                               | Removes packages no longer needed (auto-installed)            | Orphans stay on system                              |
| `-O`       | Combined with `-o`: also remove cached `.xbps` package files | Cleans `/var/cache/xbps`                                      | Cache files take up space                           |
| `-y`       | Assume yes                                                   | Skips confirmation prompt                                     | Prompts you with “Do you want to continue?”         |
| `-r`       | Remove reverse dependencies (packages that depend on target) | Uninstalls any packages that **require** the target           | Might fail if something depends on the package      |
| `-n`       | Dry-run                                                      | Simulates what would happen                                   | It actually removes the package if `-n` is not used |
| `-f`       | Force remove                                                 | Ignores dependency checks — even breaks system                | Removal will fail if dependencies are unmet         |
| `--config` | Show current config used by xbps                             | Diagnostic only                                               | Not used by normal users                            |
| `-v`       | Verbose                                                      | More output                                                   | Output stays minimal                                |
