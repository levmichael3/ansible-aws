# ansible-aws
[EXAMPLE]

ansible-playbook -i inventory/hosts project.dynamic.yml   --extra-vars "key_name=Environment key_value=dev the_role=ntp" --become --become-method=sudo
