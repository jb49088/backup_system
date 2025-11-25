### backup_system

A comprehensive backup automation system built on [Restic](https://github.com/restic/restic) with dual-repository redundancy. Backs up configuration files, code, documents, and system state to both a local Raspberry Pi (SFTP) and [Backblaze B2](https://www.backblaze.com/cloud-storage) (cloud). Features include automated retention policies, integrity checking, and single-command execution of all backup jobs.

<!-- CODE_STATISTICS_START -->

### Code Statistics

```
--------------------------------------------------------------------------------
Language                      files          blank        comment           code
--------------------------------------------------------------------------------
Bourne Again Shell               15            128            143            282
Markdown                          1             10              4             36
--------------------------------------------------------------------------------
SUM:                             16            138            147            318
--------------------------------------------------------------------------------
```
<!-- CODE_STATISTICS_END -->

<!-- PROJECT_STRUCTURE_START -->

### Project Structure

```
backup
├── logs
├── README.md
└── scripts
    ├── backup_all
    ├── backup_check
    ├── bash_backup
    ├── direnv_backup
    ├── icon_backup
    ├── ipython_backup
    ├── nvim_backup
    ├── package_backup
    ├── powershell_backup
    ├── python_backup
    ├── sql_backup
    ├── vault_backup
    ├── wt_backup
    ├── zellij_backup
    └── zshrc_backup

3 directories, 16 files
```
<!-- PROJECT_STRUCTURE_END -->
