# FileURISecurity
This is a simple set of tests which can be used to determine how a browser treats `file://` URIs.

## Current Tests
* Check if *any* `file://` access is allowed
* Check the speed of file reads
* Check if arbitrary file reads are possible (e.g. from anywhere on the filesystem and not just the same folder/child folders).
