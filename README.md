# ansible-mariadb

## Introduction
- An ansible playbook for install MariaDB.

## Prerequisites
- ansible >= 2.9

## Running the Playbook

    ansible-playbook site.yml  

## Useful Optional Arguments
- `-v through -vvvv`: Lets you increase the verbosity of the script output; -vvvv enables connection debugging.
- `-i <host-inventory-file>`: Lets you use a different host inventory file instead of the default ./inventory.ini file.
- `--tags <tag-name>`: Runs only task(s) with specific tag(s).
- `--skip-tags <tag-name>`: Skips task(s) with specific tag(s).
- `--list-tasks`: Displays all tags in a playbook.

## License
This project is licensed under the [BSD 3-Clause License](https://github.com/laineil/ansible-mariadb/blob/main/LICENSE).