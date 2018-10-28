# ansible-sonar-ldap-configuration

Add the inventory file with the UI server
```
ui ansible_host=<ui_server> ansible_ssh_user=root
```
### Run the command

```
ansible-playbook -i inventory playbook.yml
```
Enter the "ldap bindPassword" in the Command line and that's it!

If for any reason something fails, you have a backup file for your
sonar settings file (/usr/local/sonar/conf/sonar.properties) in the same
directory of the old.
