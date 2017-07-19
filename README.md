Mac provisioning for development
-------

If you haven't agreeded with xcode's liences, please type the following command and agree with it
-------

sudo xcodebuild -license;


Just paste the following lines
-------

ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)";

brew update;

brew install ansible;

git clone https://github.com/hikarine3/ansible_mac.git;

cd ansible_mac;

rm -rf ansible_mac;
wget https://github.com/hikarine3/ansible_mac/archive/master.zip;
unzip master.zip;
cd ansible_mac-master;
ansible-playbook developer-environment.yml -i hosts;


License
-------

MIT
