Windows Undefender
==================

A utility script to quickly add paths to the Windows Defender exclude list.

Adding node_modules to exclusions can significantly improve performance of npm and yarn!

Installation
------------

    npm install -g undefender

Example
-------

    cd my_folder
    undefender node_modules

Usage
-----

```
Usage:
  undefender <paths> [options]

Add or remove Windows Defender exclusion paths.

Options:
  --list        Show a list of all exclusions
  --remove      Removes requested paths from the exclusion list'
  --remove-all  Removes ALL paths from the exclusion list'
  --quiet       Suppress non-error output
  --yes, -y     Skip confirmation message
  --help        Show usage help
```
