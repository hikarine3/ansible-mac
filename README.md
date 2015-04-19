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

ansible-playbook developer-environment.yml -i hosts;

License
-------

MIT
