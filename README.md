# devops-netology
Git_first_homeworks
В каталоге terraform и подкаталогах, будут игнорироваться все файлы с расширением .tfstate, также crash логи файл crash.log
и любой лог файл с подименем crash.*.log 
Будут исключены все файлы с расширением .tfvars который могут содержать уонфиденциальную информацию, и как я понимаю ещё файлы в формате json *.tfvars.json
Все файлы содержащие в имени override _override, в форматах .tf,tf.json
Также будут игнорироваться файлы конфигурации .terraformrc,terraform.rc которые будут созданы через cli
change README
