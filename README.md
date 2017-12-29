Mac provisioning for development
-------

Just paste the following lines
-------

ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)";

brew insatll python;

brew install ansible;

git clone https://github.com/hikarine3/ansible_mac.git;

cd ansible_mac;

ansible-playbook playbook.yml -i hosts;


How to edit
-------

If you want to find necessary command line application for brew,

brew search

If you want to find necesary GUI application for brew,

brew cask search

And edit playbook.yml

License
-------

MIT

Author
-------

Hajime Kurita

An adminstrator of https://sakuhindb.com/ , http://minakoe.jp/ and so on

https://twitter.com/hikarine3

https://en.sakuhindb.com/pe/Administrator/

