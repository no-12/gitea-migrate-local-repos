# Migrate local gitea repos
Bash script to migrate local gitea repos.

## Requirements
* gitea 😉
* gitea api [token](https://docs.gitea.io/en-us/api-usage/) with admin permissions
* enable import from local server paths in app.ini
```ini
[security]
IMPORT_LOCAL_PATHS  = true
```

## Useful links
* [gitea documentation](https://docs.gitea.io/)
* [gitea api documentation](https://try.gitea.io/api/swagger)
