# group1_AmiBuild_packer

Ansible playbooks:
1. Blue server
    - with index and configuration file

2. Green Server
    - with index and configuration file

To Provision the playbook please use the following code in packer

provisioner "ansible" {
    playbook_file = "./playbooks/green/greenwebserver.yml"
  }
}

Both server were tested and working fine
