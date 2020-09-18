---
layout: page
---

## Developers

Mergin is an open platform that aims to be developer friendly, and it has been designed to allow easy integration with other software.

### Python Client

The easiest way to use Mergin programmatically is to use the Python client module. It is available in the PyPI repository and so it can be installed with `pip`:

```
pip3 install mergin-client
```

The source code of the Python client is available on GitHub in [lutraconsulting/mergin-py-client](https://github.com/lutraconsulting/mergin-py-client) repository.

### Command Line Interface

For those who prefer using terminal, there is `mergin` command line tool shipped with the Python client.
With several built-in commands, it is possible to download Mergin projects, push/pull changes, create or delete projects and more.
Please see [lutraconsulting/mergin-py-client](https://github.com/lutraconsulting/mergin-py-client) repository for more information on the usage.


### Database Sync

Integrating with other databases is an important feature provided by the DB sync tool, hosted in [lutraconsulting/mergin-db-sync](https://github.com/lutraconsulting/mergin-db-sync)
repository. It takes care of synchronization of changes between a Mergin project and a PostgreSQL database. The synchronization works both ways:
it pushes changes from PostgreSQL to Mergin and it also pulls changes from Mergin to PostgreSQL. Please see the project page for more details.
