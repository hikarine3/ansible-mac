Mac provisioning for development
-------

What you should do before use this ansible playbook
-------

sudo xcodebuild -license;

ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)";

brew update;

brew install ansible;

Set up Mac using Ansible's playbook
-------

rm -rf ansible_mac;
wget https://github.com/hikarine3/ansible_mac/archive/master.zip;
unzip master.zip;
cd ansible_mac-master;
ansible-playbook developer-environment.yml -i hosts;


License
-------

MIT
