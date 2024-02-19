# Estimates-Forecast-Template
Github Template Repository for Estimates and Forecasts Team Python projects. Use this repository to initialize new Python projects within the Estimates and Forecasts Team.

## How to use Template Repositories
New repositories can be created from template repositories via the [GitHub website GUI](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).

## Configuration of Private Data in secrets.yml
In order to avoid exposing certain data to the public it is advised to use a secrets file to store sensitive configurations *(such as server names, authorization tokens, etc...)* in addition to a standard configuration file. This file is stored in the root directory of the repository as `secrets.yml` and is included in the `.gitignore` intentionally to avoid it ever being committed to the repository.

It is important that a section is added to the project `README.md` describing how the `secrets.yml` is used and how it is structured along with an example.