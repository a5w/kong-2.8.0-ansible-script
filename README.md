# kong 2.8.0 Installation via ansible
This ansible playbook Install kong 2.8.0 on ubuntu 22.04

## Requirements:
- Ubuntu:22.04
- ansible [core 2.14.1]

## Execution
Copy `example.hosts.ini` to `hosts.ini`
Update values in hosts.ini
`ansible-playbook -i hosts.ini playbook.yml`

I have included tags with each tasks, sparate tasks can be run in case of failure
