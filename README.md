# Template to install nginx and python in the remote host using ansible. 
Commands
    
    //ping remote host
    $ ansible -i inventory.cfg -m ping all
    
    //deply playbook
    $ ansible-playbook -i inventory-cfg --ask-become-pass nginx_playbook.yml 
    
