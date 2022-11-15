
Установка Postgresql
sudo apt install postgresql - установка
sudo service postgresql start - запуск
sudo -i -u postgres - переключение на posgressql
psql - работает после запуска
create user nickin with password '111998'; alter role nickin superuser createrole createdb replication;

local user bd:
create user nickin with password '111998'; alter role nickin superuser createrole createdb replication;

rails generate rspec:install

rails generate devise:install