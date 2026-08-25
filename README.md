# Estimates-Forecast-Template
Github Template Repository for Estimates and Forecasts Team Python projects. Use this repository to initialize new Python projects within the Estimates and Forecasts Team.

## How to use Template Repositories
New repositories can be created from template repositories via the [GitHub website GUI](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).

## Configuration of Private Data in secrets files
To avoid exposing private data, store sensitive configuration values *(such as server names, usernames, and API tokens)* in a secrets file in addition to your standard configuration file.

Place the secrets file in the repository root as either `secrets.yml` or `secrets.toml`. Both file names are intentionally included in `.gitignore` so secrets are not committed.

Each project created from this template should keep a short "Secrets" section in its own `README.md` that explains its use.

### Example `secrets.yml`:

```yaml
database:
    server: your_server_name
    user: your_username
    password: your_password

api:
    token: your_api_token
```

### Example `secrets.toml`:

```toml
[database]
server = "your_server_name"
user = "your_username"
password = "your_password"

[api]
token = "your_api_token"
```