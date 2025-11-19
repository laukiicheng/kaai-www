
# Ka'ai Website
Ka'ai Academy for soccer and agility training

### Technologies
* [ReactJS](https://react.dev/learn)
* TODO: Github Actions for deployment

### Devlopment Tools
* Text editor. [Visual Studio Code](https://code.visualstudio.com/download) recommended.
* AWS IAM user. Restricted access for backend engineers.
* Github repo collaborator

### Prerequisites
* xcode for Mac users
  * To intsall run `xcode-select --install` and accept in pop up window
* [Homebrew](https://brew.sh/) Open-source pacakge manager. Use this to intall NVM.
    * `brew --version` 
      * Homebrew 5.0.2
* Install NVM - [Node version manager](https://github.com/nvm-sh/nvm)
    * `nvm --version`
      * `0.40.3`
    * `brew install nvm`
    * NVM will install Node.js and NPM CLI (command line interface)
    * MAC user will need to update the ~/.zshrc file
      * See [Stack Overflow](https://stackoverflow.com/questions/77594827/how-to-install-nvm-on-mac)
      * ```
        echo 'export NVM_DIR="$HOME/.nvm"' >> ~/.zshrc
        echo '[ -s "$(brew --prefix nvm)/nvm.sh" ] && \. "$(brew --prefix nvm)/nvm.sh"' >> ~/.zshrc
        echo '[ -s "$(brew --prefix nvm)/etc/bash_completion.d/nvm" ] && \. "$(brew --prefix nvm)/etc/bash_completion.d/nvm"' >> ~/.zshrc
        source ~/.zshrc
        ```
* Install Node.js use NVM
    * `node --version`
      * `v24.11.1`
    * `npm --version`
      * `11.6.2`
    * `nvm install --lts` (Long Term Support)
* NVM Commandas
    * List node versions 
      * `nvm ls`
    * Use a specific NPM version
      *  `nvm use <version_number>`
* Github Account and git CLI
    * `git --version` `git version 2.50.1 (Apple Git-155)`
    * [Github SSH](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)


