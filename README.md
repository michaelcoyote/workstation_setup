## workstation setup playbook

Change into the root directory.  
Install the requirements with `ansible-galaxy install -r requirements.yml`  
Use `ansible-playbook ./main.yml -i ./inventory -K` to set up a macbook.  
The tags homebrew, mas, and dotfiles are supported but mas doesn't do much at this point.  

### TODO

Only supports mac for now but eventually we should be able to support ubuntu or etc..  


