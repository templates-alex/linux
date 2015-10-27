# My notes

* home account for Alex Davis

* packages required to install pyenv
```
apt-get install -y make build-essential libssl-dev zlib1g-dev libbz2-dev \ libreadline-dev libsqlite3-dev wget curl llvm
```

* install pyenv
```
git clone https://github.com/yyuu/pyenv.git ~/.pyenv
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bash_profile
echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bash_profile
echo 'eval "$(pyenv init -)"' >> ~/.bash_profile
```

* install nvm for nodejs
```
curl https://raw.githubusercontent.com/creationix/nvm/v0.25.0/install.sh | bash
```

* install rvm
```
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3
\curl -sSL https://get.rvm.io | bash -s stable --rails
```
* install gvm
```
apt-get -y install unzip openjdk-7-jdk
curl -s get.gvmtool.net | bash
gvm install grails
```

* install neobundle for vimrc to work
```
curl https://raw.githubusercontent.com/Shougo/neobundle.vim/master/bin/install.sh | sh
```

