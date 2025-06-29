# WORKING WITH ANSIBLE
___
***install ansible***

<li> sudo apt update<li> </li>
 

## Управление SSH key 
<li>ssh-keygen - генерация ключа ( при генерации ключа даем ему своё,  понятное нам название например ansible)

## Содзаем файл конфигурции ***ansible.cfg*** 
    [default]
    infentory = infentory
    privaty_key_file = ~/.ssh/ansible