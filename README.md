# ansible-sonar-ldap-configuration

Add the inventory file with the UI server
```
ui ansible_host=<ui_server> ansible_ssh_user=root
```
###Run the command

```
ansible-playbook -i inventory playbook.yml
```
Enter the ldap bindPassword and that's it!

If for any reason something fails, you get a backup file for your
sonar settings file (/usr/local/sonar/conf/sonar.properties)
