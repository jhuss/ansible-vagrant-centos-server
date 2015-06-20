## Usage:
on directory of cloned repository execute:

```ansible-playbook -i inventory/vagrant --private-key=<VAGRANTFILE_DIR>/.vagrant/machines/default/virtualbox/private_key -s -e "target=vagrant" <FILE>.yml --tags "<TAG>"```

### Format:
Option | Description
--- | ---
VAGRANTFILE_DIR | path of directory that contain file "Vagrantfile"
FILE | Playbook file name
--tags TAG | (optional) run only specific task
