#Modification 1

.gitignore будет игнорировать следующие файлы:

  1. Директорию терраформ и все файлы внутри, независимо от расположения в репозитории
  2. Любые Файлы, включающие имя tfstate
  3. Файл с логами ошибок
  4. Все файлы tfvars, которые содержать конф. данные, такие как пароли, ключи и прочее.
  5. Любые Override файлы, используемые для перезаписи локалных источников
  6. Конфигурационные файлы terraform
