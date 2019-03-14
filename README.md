These scripts are used for the "Deploy to AWS with Ansible and Terraform" course on Linux Academy. 

#setting up key on server
ssh-keygen
/root/.ssh/<keyname>
  
#key forwarding - do every time logging in
ssh-agent bash
ssh-add ~/.ssh/<keyname>
ssh-add -l  

export PATH=$PATH:/bin/terraform
