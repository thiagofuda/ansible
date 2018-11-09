ansible-playbook -v -b -i ./gandalf_sre/automacao/playbook/hosts -e 'STATUS=restart apache' -l infra-qa ./gandalf_sre/automacao/playbook/deploy/deploy.yml --skip-tags configuration
