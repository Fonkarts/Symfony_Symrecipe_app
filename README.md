# Symfony Painter Project

This project is a food recipe app, made with Symfony 6.2.  
More details coming soon.

First hosted on GitLab : https://gitlab.com/Fonkarts/symfony_symrecipe_app

## Development Environment

### Requirements

- PHP 8.1 or higher
- Composer
- Symfony 6.2
- Symfony CLI

You can check the requirements (except for Docker & Docker-compose) by executing this symfonyCLI command :

```bash
symphony check:requirements
```

### Installation

- Clone this project in your folder
- Then open a command prompt and :
```bash
cd your_folder/
composer install
```

### Run the environment

```bash
cd your_folder/
symfony serve -d
```

### Run tests

```bash
php bin/phpunit --testdox
```
