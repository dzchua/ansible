# ansible
The proper format of how ansible directory is done if the playbook gets larger. Run the setup.sh file first to create virtual environment and required packages.

### How to manage role
/path/to/role are all the required roles
./setup/role_update.sh to update the roles

### How to run the file
ansible-playbook -i .ini /path/to/playbook
