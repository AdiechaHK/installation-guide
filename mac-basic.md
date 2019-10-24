# Mac Development System Installtion

### Move your data (from old system to new)

### Installation

#### Install Brew
    
  ```
  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  ```
  
[More details](https://brew.sh)


#### Install oh-my-zsh

  ```
  sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
  ```

[More details](https://github.com/robbyrussell/oh-my-zsh)


#### Import Terminal theme

- Open Terminal
- Goto menu `Terminal` -> `Preferances` -> `Profile`
- import this theme [HK-Terminal](HK.terminal)
    

#### Install software if not installed

- docker
- sequalPro
- slack
- bravo
- chrome
- vscode or sublime (according to the preferance)
- postman (login from google after installtion)
- gitx (There is special case if you install it in `High Sierra`) [create alias using `alias gitx='open -a GitX .'`]
- gitflow (Command: `brew install git-flow`)

_Note: You can find `.dmg` file in publically shared folder_
  

#### Set Git Config

    git config --global user.name "Harikrushna V Adiecha"
    git config --global user.email "adiechahari@gmail.com"


#### Generate and upload SSH

    ssh-add -K ~/.ssh/id_rsa
    pbcopy < ~/.ssh/id_rsa.pub
    
[Generate SSH](https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

[Add SSH to Github](https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account)

  
#### PHP

install php or check php version and if it is older then install via brew and link that and start brew service for php. Then also it is shows old version then restart pc once

#### Mysql


#### Composer

    php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
    php -r "if (hash_file('sha384', 'composer-setup.php') === 'a5c698ffe4b8e849a443b120cd5ba38043260d5c4023dbf93e1558871f1f07f58274fc6f4c93bcfd858c6bd0775cd8d1') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
    php composer-setup.php
    php -r "unlink('composer-setup.php');"
    
Now check if `composer` command works or not, if not then we need to make it globally available using following command.
    
    mv composer.phar /usr/local/bin/composer

If it's installed in home directory then, we need to export it's path
    
    export PATH="$PATH:$HOME/.composer/vendor/bin"  


[More details](https://getcomposer.org/download/)

#### Valet installation

    composer global require laravel/valet

[More details] (https://laravel.com/docs/valet#installation)


#### Sublime Setup

#### Sharing setting

Check following options
- Screen Share
- File Share
- Remote Login

_Others should be unchecked_

#### Login and verify the following

- [Clockify](https://clockify.me/)
- [Slack](https://slack.com/signin)
- [Gmail](https://mail.google.com) (also turn on sync, so all data will be synced)
- [Github](https://github.com)
- [Gitlab](https://gitlab.com)
- [Asana](https://app.asana.com)
- [Nexus](http://nexus.improwised.com)
- [Station](https://station.improwised.com)
  



