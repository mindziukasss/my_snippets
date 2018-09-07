# symfony_snippets with docker

#### make migrations, entities, controllers etc.

bin/console make:{migration/entity/controller}

#### migrate

bin/console doctrine:migrations:migrate

#### drop database

bin/console doctrine:database:drop --force

#### create database

bin/console doctrine:database:create

#### load fixtures

bin/console doctrine:fixtures:load

#### flush database with entity structure

bin/console d:s:u --force

#### start symfony server

bin/console server:run