
## About Us

Turso is an edge database, built by the creators of [libSQL](github.com/libsql), an Open Contribution fork of SQLite.

Turso allows you to develop locally and deploy globally to many locations around the world.
Replication is easy and affordable, and it is fully controllable through an API.

## Open Source

The Turso database is fully Open Source, and we offer a managed service. However, the core code of the database doesn't live in this organization, but
in the [libSQL organization] instead. Relevant repositories:

- [libSQL core](https://github.com/libsql/libsql): libSQL, an Open Contribution fork of SQLite. It can be used as a library, but add features like WASM User Defined Functions, and Write-Ahead-Log virtualization, which we use for data replication.
- [libSQL server](https://github.com/libsql/sqld): a server-mode service for libSQL. 

