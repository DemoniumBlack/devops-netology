# devops-netology
Репозиторий DevOps Netology

Внес какие-то изменения.

В файле terraform.gitignore будут проигнорированы следующие каталоги и файлы:

Локальные директории Terraform:
Любые пути к содержащие в себе каталог terraform - ***/.terraform/*

Файлы **.tfstate* и *.tfstate.* - файлы с расширением tfstate и файлы содержащие в себе слово tfstate.
Файлы логов крэшей сервиса crash.log и crash.*.log - файлы crash.log и файлы содержащие в себе все после слова crash, например, там может быть дата.
Файлы, которые могут содержать в себе пароли, приватные ключи и другие секреты *.tfvars и *.tfvars.json - файлы с расширением tfvars и файлы с расширением *.tfvars.json
Файлы локальных ограничений override.tf override.tf.json *_override.tf *_override.tf.json.
Конфигурационные файлы CLI Terraform .terraformrc terraform.rc