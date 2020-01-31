# Django starter template

# Virtual enviroments

Please create a virtual enviroments on a private folder, suggested ~/.venvs

# How to use it

```sh
$ git clone --depth=1 --branch=master git://someserver/somerepo dirformynewrepo
$ rm -rf ./dirformynewrepo/.git
```

# How it works

- **DJANGO_ENV**: Option to load setting by enviroment, the available options are Development, QA, Development and Defaults. It's not case sensitive. DEFAULT: Defaults.

# Enviromental variables for production database

- **POSTGRES_DB**: Database name.
- **POSTGRES_USER**: Database production user.
- **POSTGRES\_USER_PASSWORD**: Database production user password.
- **POSTGRES_HOST**: Database URL for remote server.
- **POSTGRES_PORT**: Database port. Default: 5432.


