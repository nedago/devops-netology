# devops-netology Денис Поляков
## Задание №1

Файлы будут проигнорированы в будущем благодаря добавленному в папку terraform `.gitignore`:
- `**/.terraform/*` - игнорирует все файлы в скрытой папке ".terraform" где бы она не находилась
- `*.tfstate` - игнорирует все файлы с расширением ".tfstate"
- `*.tfstate.*` - игнорирует все файлы где в середине имени присутствует ".tfstate."
- `crash.log` - игнорирует файл с полным совпадением написания"crash.log"
- `*.tfvars` - игнорирует файл с расширением "*.tfvars"
- `override.tf` - игнорирует файл с полным совпадением написания "override.tf"
- `override.tf.json` - игнорирует файлы с полным совпадением написания "override.tf.json"

- `*_override.tf` - игнорирует файлы с окончанием "_override.tf"
- `*_override.tf.json` - игнорирует файлы с окончанием "_override.tf.json"
- `.terraformrc` - игнорирует скрытый файл с свопадением написания ".terraformrc"
- `terraform.rc` - игнорирует файл с свопадением написания "terraform.rc"

Add changes step1 to the file