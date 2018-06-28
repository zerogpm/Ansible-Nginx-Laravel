## About Ansible Laravel 5.6

Some other commands you’ll be running often in a Laravel project:

## Run Ansible full build
` ansible-playbook ./playbook.yml -i ./hosts.ini --user=username --ask-become-pass`

## Part of the build with tags
`ansible-playbook ./playbook.yml -i ./hosts.ini --user=username --ask-become-pass -t test`
