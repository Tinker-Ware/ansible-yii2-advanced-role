# Ansible Yii2 Advanced Framework role

This role will install a working Yii2 Advanced template.

### Variables
`yii_git_repo`: Url for the git repo. Example: `https://github.com/Tinker-Ware/yii2-crud.git`
`yii_git_version`: Branch or tag to use from the repo. Example: `master`
`yii_extra_flags`: Extra options tu run with composer update. Example: `"--no-dev"`


## Usage

Playbook file:

```
- hosts: myserver
  roles:
      - yii2-advanced
```
