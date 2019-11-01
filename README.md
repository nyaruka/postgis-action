# PostgreSQL GitHub Action

This [GitHub Action](https://github.com/features/actions) sets up a PostgreSQL database with PostGIS.

# Usage

See [action.yml](action.yml)

Basic:
```yaml
steps:
- uses: nyaruka/postgis-action@v1
  with:
    postgresql version: '11'  # See https://hub.docker.com/_/postgres for available versions
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
