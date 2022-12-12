# Symfony Painter Project

This project is a painter website, made with Symfony 5. More details coming soon.

## Development Environment

### Requirements

- PHP 8.1
- Composer
- Symfony 6.2
- Symfony CLI
<!-- - Docker
- Docker-compose -->

You can check the requirements (except for Docker & Docker-compose) by executing this symfonyCLI command :

```bash
symphony check:requirements
```

### Run the environment

```bash
docker-compose up -d
symfony serve -d
```

### Run tests

```bash
php bin/phpunit --testdox
```
