# PostgreSQL GitHub Action

This [GitHub Action](https://github.com/features/actions) sets up a PostgreSQL database with PostGIS, 
using the [postgis:postgis](https://hub.docker.com/r/postgis/postgis) Docker image.

# Usage

See [action.yml](action.yml)

Basic:
```yaml
steps:
- uses: nyaruka/postgis-action@v2.1.0
  with:
    postgresql version: '12'
    postgis version: '2.5'
    postgresql password: 'sesame'
    postgresql arguments: '--jit=off'
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
