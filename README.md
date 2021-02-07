# ansible-gitlab
install on-perm gitlab using ansible

simple ansible playbook to install on-perm gitlab on your servers.

useful when you want to install gitlab on several servers.

add your servers addresses to hosts file and use the below command to install gitlab on them:
    
          ansible-playbook -i hosts gitlab.yml
