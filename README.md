Setup

    1. Move hosts file to /etc/ansible/hosts. Change hosts IP addresess according to actual ones.
    2. Move KPair.pem file to ansible host home directory and add your private key for connecting to ec2 instances there.
    3. Run command: 
    # sudo ansible-playbook envs-playbook.yml
