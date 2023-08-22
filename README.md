# dotfiles
Mixture of dotfiles for tmux, nano, vim, neovim, zsh, and Ansible playbooks to install it on a mixture of Operating Systems

# Usage
'''
python -m venv venv
source venv/bin/activate
pip install --upgrade pip
pip install -R requirements.txt
bash requirements.sh

ansible-playbook playbooks/bootstrap
'''
