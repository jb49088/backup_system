### backup_system

A comprehensive backup automation system built on [Restic](https://github.com/restic/restic) with dual-repository redundancy. Backs up configuration files, code, documents, and system state to both a local Raspberry Pi (SFTP) and [Backblaze B2](https://www.backblaze.com/cloud-storage) (cloud). Features include automated retention policies, integrity checking, and single-command execution of all backup jobs.

<!-- CODE_STATISTICS_START -->

### Code Statistics

```
--------------------------------------------------------------------------------
Language                      files          blank        comment           code
--------------------------------------------------------------------------------
Bourne Again Shell               16            134            151            289
Markdown                          1              8              4             36
--------------------------------------------------------------------------------
SUM:                             17            142            155            325
--------------------------------------------------------------------------------
```
<!-- CODE_STATISTICS_END -->

<!-- PROJECT_STRUCTURE_START -->

### Project Structure

```
backup_system
├── logs
├── README.md
└── scripts
    ├── backup-all
    ├── backup-check
    ├── bash-backup
    ├── direnv-backup
    ├── icon-backup
    ├── ipython-backup
    ├── nvim-backup
    ├── package-backup
    ├── powershell-backup
    ├── python-backup
    ├── sql-backup
    ├── sqliterc-backup
    ├── vault-backup
    ├── wt-backup
    ├── zellij-backup
    └── zshrc-backup

3 directories, 17 files
```
<!-- PROJECT_STRUCTURE_END -->
