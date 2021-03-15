# Symfony Project

Site pour un créateur de mode

## Environnment de dév

### Pré-requis

* PHP 7.4
* Composer
* Symfony CLI
* Docker
* Docker-compose

### Ajouter des données de tests

```bash
symfony console doctrine:fixtures:load
```

### Lancer des test

```bash
php bin/phpunit --testdox
```