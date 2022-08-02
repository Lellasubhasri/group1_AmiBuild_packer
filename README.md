# group1_AmiBuild_packer

provisioner "ansible" {
    playbook_file = "./playbooks/green/greenwebserver.yml"
  }
}
