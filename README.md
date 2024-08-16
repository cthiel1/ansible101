# ansible101

## Installation on Mac/Linux
sudo pip3 install ansible


## Running the playbook
ansible-playbook -i localhost my_playbook.yml

## Challenges
* Run the playbook twice in a row
* Run the playbook modules as ad-hocs
* Turn our ping ad-hoc into a playbook task
* Variablize the content and/or name of the file (Hint: "{{jinja syntax}}" )
* Use the 'lineinfile' module to update the hello file after it's been created
