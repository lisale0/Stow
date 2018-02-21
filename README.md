# Stow
People obtain draw conclusions about their health prematurely when symptoms are noticed.  Stow helps users and patients stow their positive and negative experiences about their health, these experiences will be displayed back to the user in a daily, weekly, or monthly basis on a bubble graph.  The bubble graph is not displayed on a x/y axis to avoid biases and drawing conclusions for the user.  

## Getting Started

## Requirements
### Ubuntu Machine
You can use last version of Ubuntu or any other OS 
(Note: unit test done on Ubuntu 14.04).



### Ruby 2.X+
```
sudo apt-get update
sudo apt-get install git-core curl zlib1g-dev build-essential libssl-dev libreadline-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev libcurl4-openssl-dev python-software-properties libffi-dev


cd
git clone https://github.com/rbenv/rbenv.git ~/.rbenv
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(rbenv init -)"' >> ~/.bashrc
exec $SHELL

git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build
echo 'export PATH="$HOME/.rbenv/plugins/ruby-build/bin:$PATH"' >> ~/.bashrc
exec $SHELL

rbenv install 2.3.1
rbenv global 2.3.1
ruby -v

```




#### Configure AWS




## Author(s)
* Lisa Leung 
