# Shpora

GitSubModule

Создание
1. git submodule add <URL-репозитория> <Путь где лежит сабмодуль(Core)>

Обновление, при клонировании проекта с сабмодулем

2. git submodule update --init --recursive


3. Удаление сабмодуля <Core>
   3.1 git submodule deinit -f <Core>
   3.2 git rm -f <Core>
   3.3 rm -rf .git/modules/<Core> (Windows - rmdir /s .git\modules\<Core>)
   3.4 Если 3.3 не сработтало Remove-Item -Recurse -Force .git\modules\<Core>

Database PgSql

1.
