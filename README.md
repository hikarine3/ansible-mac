What is this repostitory for?
-------

Do provisioning based on script for Mac for develoopment and so on

This will be useful when you have to move to new PC.

You can edit playbook.yml based on your necessity and can use this one as the starting template for that purpose.

Just paste the following lines
-------

```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)";

brew insatll python;

brew install ansible;

git clone https://github.com/hikarine3/ansible-mac.git;

cd ansible-mac;

ansible-playbook playbook.yml -i hosts;
```

How to edit
-------

If you want to find necessary command line application for brew,

```
brew search
```

If you want to find necesary GUI application for brew,

```
brew cask search
```

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
