Mac provisioning for development
-------

What you should do before use this ansible playbook
-------

sudo xcodebuild -license;

ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)";

brew update;

brew install ansible;

git clone https://github.com/hikarine3/ansible_mac.git;

cd ansible_mac;

ansible-playbook developer-environment.yml -i hosts;

License
-------

MIT
