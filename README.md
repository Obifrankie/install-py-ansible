#install-py

This CI script is writing in yaml

This script automates the setup of python environment running on ansible

It main point of entry is the main.yml file

It has 1 workflow/task which is the -configure-server

The configure server workflow handles depenedenciesand installs pm on the target machine.
The path of the apache workflow is roles/apache/tasks/main.yaml

To run this script localy ensure that you have ansile configured locally by running the show command python3 -m pip show ansible

and run the script with the following command ansible-playbook main.yml
