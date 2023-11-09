# dotenv-vault sample

## usage

### login

```bash
$ npx dotenv-vault@latest login
```

this takes you to vault.dotenv.org and authenticate with your email (you need to be part of team of this project)
After authentication succeeded, .env.me file is created. This works like secret key to pull .env file

### pull

```bash
$ npx dotenv-vault@latest pull
```

This pull .env file

### Environments

pull each environments .env

```bash

$ npx dotenv-vault@latest pull $environment
```

This pull .env.$environment file

## CI/CD

### github actions
https://www.dotenv.org/docs/languages/nodejs/github-actions

