
## Установка Postgresql
sudo apt install postgresql - установка
sudo service postgresql start - запуск
sudo -i -u postgres - переключение на posgressql
psql - работает после запуска
create user nickin with password '111998'; alter role nickin superuser createrole createdb replication;

local user bd:
create user nickin with password '111998'; alter role nickin superuser createrole createdb replication;

rails generate rspec:install

rails generate devise:install

## Покрытие тестами

gem `simplecov`
https://github.com/simplecov-ruby/simplecov

Генерирует файл с анализам тестового покрытия `./coverage/index.html`
Результат высчитывается во время теста, поэтому нужно пройтись по всем спекам.

Главные показатели:
* **%covered** процент покрытых строк, т.е. сколько полезных (т.е. не считая пустых, коментариев и т.д.) строк было задействовано во время теста
* **Branch Coverage** процент покрытия однострочных ветвлений, т.е. условий, записанных в одну строку, типа `if ? true : false`
