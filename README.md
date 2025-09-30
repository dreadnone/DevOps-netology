# DevOps-netology
checked
#Игнор файлов для Terraform
#файлы, расположенные в директории .terraform/
#все файлы с расширениями
 *.tfstate
 *.tfstate.*
#журнылы сбоев 
crash.log
crash.*.log
#файлы с параметрами 
*.tfvars
*.tfvars.json
#структура файлом override
override.tf
override.tf.json
*_override.tf
*_override.tf.json
#файл блокировки Terraform 
.terraform.tfstate.lock.info
#конфигурационные файлы
.terraformrc
terraform.rc
