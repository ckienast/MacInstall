# Setup new machine

## General
* [ ] Install OS X updates
* [ ] Install homebrew  
``/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"``
* [ ] Install Google Chrome  
``brew cask install google-chrome``
* [ ] Install [usgerman](https://github.com/janv/usgerman) keyboard layout
* [ ] Register AppleCare if not done already
* [ ] Set keyboard response (stroke speed, repeat speed)
* [ ] Setup iCloud accounts
* [ ] Install Slack and login to 9elements
* [ ] Install 1password
  * 9elements via Gmail
* [ ] Install Sketch

## Dev related
* [ ] Install [iTerm2](https://www.iterm2.com) or [Hyper](https://github.com/zeit/hyper)
* [ ] Install ZSH shell and make it default  
``brew install zsh``  
``chsh -s /bin/zsh``
  * [ ] Install oh-my-zsh  
  ``sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"``
* [ ] Update git to latest version
  * [ ] add ~/.gitconfig
  * [ ] add ~/.gitignore
* [ ] Install Atom (atom.io)  
``brew cask install atom``
  * [ ] use sync-settings if possible
* [ ] Install rvm  
``\curl -sSL http://get.rvm.io | bash -s stable --ruby``
  * [ ] install latest ruby and make it default globally  
  ``rvm install -l``  
  ``rvm --default use LATEST``
* [ ] Install nvm  
  ``curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.1/install.sh | bash``
  * [ ] Add nvm to .zshrc
  * [ ] Install latest nvm  
  ``nvm ls-remote``  
  ``nvm install LATEST``
* [ ] Install yarn  
``brew install yarn``
* [ ] Install PostgreSQL  
``brew install postgresql``
  * [ ] Start PostreSQL service
  ``brew services start postgresql``
* [ ] Install Rails  
``gem install rails``
* [ ] Install Cyberduck  
``brew cask install cyberduck``
* [ ] Install GitKraken  
``brew cask install gitkraken``
* [ ] Install Postman  
``brew cask install postman``
* [ ] Install Postico  
``brew cask install postico``
* [ ] Install VirtualBox  
``brew cask install virtualbox``
* [ ] Install Dash  
``brew cask install dash``
* [ ] Install 9elements certificates
* [ ] Copy .ssh/ folder from your old machine or create new (old keys recommended!)
* [ ] Copy old /etc/hosts

## Mobile Dev
* [ ] Install Xcode and start it to agree license
* [ ] Install Android Studio  
``brew cask install android-studio``
  * [ ] JDK
  * [ ] Android SDK
  * [ ] Emulator
* [ ] Install react native globally  
``yarn global add react-native``

## Optional
``brew cask install APPNAME``
* [ ] Spotify
* [ ] Skype
* [ ] Dropbox
* [ ] Google Drive
* [ ] Twitter
* [ ] WhatsApp
* [ ] ImageOptim
* [ ] Spectacle
* [ ] Rocket
* [ ] KeepingYouAwake
