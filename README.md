# PostgreSQL GitHub Action

This [GitHub Action](https://github.com/features/actions) sets up a PostgreSQL database with PostGIS.

# Usage

See [action.yml](action.yml)

Basic:
```yaml
steps:
- uses: nyaruka/postgis-action@v1
  with:
    postgresql version: '12'
    postgis version: '2.5'
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
