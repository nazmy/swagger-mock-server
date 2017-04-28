## IInstalling NVM and NodeJS:
a) Install NVM using brew

```
brew install nvm
mkdir ~/.nvm
```
b) Add the following in `.bash_profile`

```
export NVM_DIR=~/.nvm
source $(brew --prefix nvm)/nvm.sh
```

c) Activate and Verify NVM Installation

```
source ~/.bash_profile
echo $NVM_DIR
nvm --version
```

d) Install NodeJS

`nvm install [VERSION]`

## Run the application
a) Install the node dependencies:
`npm install`

b) Run the swagger-mock
`npm start`

Note : Edit index.js to point to different .yaml file and change the port
