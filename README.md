### Ansible-salt-master
This Ansible playbook will help you to configure a Salt Master.

### Pre-reqs
This playbook has been tested in an environment with the setting below:
<table> 
  <tr>
    <th>os</th>
    <th>os_family</th>
    <th>os_version</th>
    <th>CPU's</th>
    <th>Memory</th>
  </tr>
  <tr>
    <td>Linux</td>
    <td>Red Hat (Oracle Linux, CentOS & Red Hat)</td>
    <td>8</td>
    <td>2</td>
    <td>4GB</td>
  </tr>
</table>

### How to use
###### Clone repo
Clone this GIT repo:
```bash
$ git clone XX
```
###### Change inventory.ini
Change the inventory.init file:
```ini
[hosts]
192.168.0.126 # Change here
```
###### Run playbook
```bash
ansible-playbook -i inventory.ini playbook.yml
```