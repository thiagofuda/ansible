ansible-playbook -v -b -i ./gandalf_sre/automation/playbook/hosts -e 'STATUS=restart apache' -l infra-qa ./gandalf_sre/automation/playbook/deploy/deploy.yml --skip-tags configuration
