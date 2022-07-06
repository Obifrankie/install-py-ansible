#install-py

This CI script is writing in yaml

This splaybook automates the setup of python environment running on ansible

It main point of entry is the main.yml file

It has 1 play which is the -configure-server

The configure server play handles depenedencies and installs pm on the target machine.
The path of the configure-server play is roles/apache/tasks/main.yaml

To run this playbook localy ensure that you have ansile configured locally by running the show command python3 -m pip show ansible

and run the playbook with the following command ansible-playbook main.yml
