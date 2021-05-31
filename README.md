![cover](https://user-images.githubusercontent.com/15225447/110500177-38051000-80f9-11eb-87fc-67c421f222ce.png)

# ForumÉduc 

__ForumÉduc__ (Forum Éducatif) est un projet open source où les contributeurs offrent leurs connaissances et leurs compétences informatiques afin de créer un Forum pour les étudiants de pole universitaires de Bouïra.

## Rejoignez nous

Vous n'avez pas besoin de rejoindre les gens mais peut-être les idées, Alors vous êtes peut-être surexcité par les nouvelles technologies et le développement ? notre communauté est ouvert à toutes le monde.

**Contribuer**

Pour vous contribuer consulter le guide _GitHub_ contribution à un projet  sur : [git-scm.com](https://git-scm.com/book/fr/v2/GitHub-Contribution-%C3%A0-un-projet)

## Environnement de développement

Comme vous voyez, nous venons de commencer notre premier pas sur `Laravel`, et de faire les premières configurations sur Git.

## Prérequis:

```
- NodeJS
    - React
    - Axios
    - ...
- PHP 7.3 ou plus
    - Laravel 7.X
    - Extensions PHP
        - sqlite3
        - php*-mysql
        - php*-xml
        - php*-mbstring
        - xdebug
        - xdebug
        - pdo 
        - pdo_pgsql
        - pdo_mysql
- Outils
    - git
    - npm
```

## Docker-compose

_Optional but requested_

```
- Docker
    - Conteneur
        - Stack
            - MySQL
            - PostgreSQL
            - Redis
            - Adminer
```

## Espace de développement

```
git clone https://github.com/dcbouira/forumeduc.git

cd ./forumeduc
```

Pour installer les dépendances PHP:
```
composer install
```

Configurer Laravel
```
cp .env.simple .env
php artisan key:generate
```

Et les dépendances JS:
```
npm install

puis..
npm run dev
```






## Licence
Educational Community Licence., Version 2.0 (ECL-2.0)
