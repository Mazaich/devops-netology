# devops-netology
Тест 1

Судя по содержанию файла (вероятно, .gitignore для Terraform), в будущем будут проигнорированы следующие файлы и директории:
Локальные директории Terraform:
.terraform/ (включая все содержимое).

Файлы состояний Terraform:
*.tfstate (например, terraform.tfstate).
*.tfstate.* (например, terraform.tfstate.backup).

Файлы логов аварийных завершений:
crash.log.
crash.*.log (например, crash.12345.log).

Файлы переменных Terraform:
*.tfvars (например, terraform.tfvars).
*.tfvars.json (например, secrets.tfvars.json).

Файлы переопределений ресурсов:
override.tf, override.tf.json.
*_override.tf, *_override.tf.json (например, prod_override.tf).

Файлы блокировки состояния:
.terraform.tfstate.lock.info.

Конфигурационные файлы CLI Terraform:
.terraformrc, terraform.rc.
Добавил новую строку ветку fix
