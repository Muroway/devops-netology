#Новая строчка
# devops-netology
# Local .terraform directories
**/.terraform/* - игнорировать файл .terraform в любых директориях

# .tfstate files
*.tfstate -  игнорировать файлы с расширением .tfstate
*.tfstate.* - игнорировать файлы в расширении которых есть .tfstate.

# Crash log files
crash.log - игнорировать файл crash.log
crash.*.log - игнорировать файл crash.*.log c любым промежуточным расширением

# Exclude all .tfvars files, which are likely to contain sensitive data, such as
# password, private keys, and other secrets. These should not be part of version
# control as they are data points which are potentially sensitive and subject
# to change depending on the environment.
*.tfvars - игнорировать файлы в которых может быть не предназначенная для публикации информация с раширением .tfvars
*.tfvars.json - игнорировть файлы с расширением .tfvars.json

# Ignore override files as they are usually used to override resources locally and so
# are not checked in
override.tf - игнорировать файл override.tf
override.tf.json - игнорировать файл override.tf.json
*_override.tf - игнорировать файл в названии которого _override.tf
*_override.tf.json - игнорировать файл в названии которого есть _override.tf.json

# Include override files you do wish to add to version control using negated pattern
# !example_override.tf

# Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
# example: *tfplan*

# Ignore CLI configuration files
.terraformrc - игнорировать файлы конфигурации командной строки с расширением .terraformrc
terraform.rc - игнорировать файл terraform.rc
