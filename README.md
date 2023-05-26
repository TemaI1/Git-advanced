- git init — команда инициализации репозитория в текущей папке.

- git clone path — команда, которая клонирует удалённый репозиторий
path(https://github.com...)

- git remote add origin path — команда, которая устанавливает в
настройках локального репозитория путь к удалённому репозиторию path

- git push -u origin master — команда, которая отправляет изменения
из локального репозитория на сервер

- git merge origin/master - влить нужные изменения

- git remote show origin - позволяет просмотреть, какие локальные ветки связаны с
ветками удалённого репозитория

- git fetch - скачать все изменения из ветки удалённого репозитория в локальный, но без обновления

- git log origin/main ^main - посмотреть, какие изменения были внесены в удалённую ветку

- git diff hash - просмотреть cодержимое каждого такого коммита, (hash)хэш коммита

- git pull - влить удалённую ветку в свою локальную

- git diff file просмотреть изменения, относительно последней закоммиченной версии

- git diff просмотреть все изменения

- git diff 5562fa353 d5e73e4b2 file просмотреть изменения между коммитами в файле

- git diff 5562fa353 d5e73e4b2 посмотреть изменения во всём проекте между коммитами

- git blame file посмотреть изменения, какими пользователями вносились

- git restore file вернуть файл к исходному состоянию

- git restore --staged file вернуть из индекса

- git reset --hard удалить все изменения

- git clean -f удалить untracked файлы

- git rm --cached file удалить из отслеживания

- git restore --staged index.html отменить версию файла

- git restore file удалить изменения

- git revert b45a983 отменить как коммит

- git reset --soft C в мягком варианте

- git reset --mixed C в смешанном варианте

- git reset --hard C жёсткий вариант команды

- git reset --merge hash отменить такое слияние

- git merge --abort  если слияние не произошло из-за конфликтов, моожно отменить

- git stash отложить изменения 

- git stash pop вернуть более ранние изменения из отложенных

- git stash drop отменить последнюю порцию отложенных изменений
