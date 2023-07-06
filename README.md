# learning-ansible

Ansbile command:
u - user
k - password
-e declare variable
i = inventory

ansible-playbook -i inventory -u centos -k 02-vars.yml -e URL=cli.example.com


Ansible Run Time Variables
From a task output (register)
Set a variable using task (set_fact)

attrubites called as output
please check user module in ansible documents ( We can get the more info)
