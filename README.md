# DevOps-Netology - `Горелов Николай`


1. [Системы контроля версий](https://github.com/gorelovniko/devops-netology/blob/main/GIT-01.Системы%20контроля%20версий/Системы%20контроля%20версий.md)
   * Благодаря Terraform/.gitignore при отправки на github.com будут проигнорированы для добавления файлы содержащие следующие буквосочетания:
     - Локальные файлы Terraform (.terraform/, *.tfstate)
     - Файлы логов (crash.log, crash.*.log)
     - Файлы переопределения (override.tf, override.tf.json, *_override.tf, *_override.tf.json)
     - Файлы с чувствительными данными (*.tfvars, *.tfvars.json)
     - Локальные конфигурационные файлы (.terraformrc, terraform.rc)  
     Знак звездочки(*) означает любые знаки в имени файлов. Выражение ".terraform/" добавляет всю скрытую папку. Словосочетание terraform.rc указывает на конкретный файл.

2. [Основы Git](https://github.com/gorelovniko/devops-netology/blob/main/GIT-02.%20Основы%20GIT/Основа%20GIT.md)