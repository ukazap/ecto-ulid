# Change Log

## 0.1.0 (2018-06-06)
### Added
* Generate ULID in Base32 or binary format.
* Generate ULID for a given timestamp.
* Autogenerate ULID when used as a primary key.
* Supports reading and writing ULID in a database backed by its native `uuid` type (no database
  extensions required).
* Supports Ecto 2.x.
* Supports Elixir 1.2 and newer.
* Tested with PostgreSQL and MySQL.