# dotfiles-rails

## Download the dotiles to your home folder

`.eslintrc.yml`

`.reek.yml`

`.rubocop-base.yml`

`.rubocop.yml`

## Install the required gems

> You will have to do this step for every single project

`‌gem install solargraph`

`gem install rubocop`

`gem install rubocop-rspec`

`gem install reek -v 5.0.2`

## Install this extensions

- [Rails](https://marketplace.visualstudio.com/items?itemName=bung87.rails): Ruby on Rails support for Visual Studio Code
- [vscode-gemfile](https://marketplace.visualstudio.com/items?itemName=bung87.vscode-gemfile): Provide hover link in Gemfile refers to online site
-	[Ruby solargraph](https://marketplace.visualstudio.com/items?itemName=castwide.solargraph): Code completion, intellisense, and inline documentation
- [ESlint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): Integrates ESLint JavaScript into VS Code.
- [Ruby](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby): Ruby language support and debugging for Visual Studio Code
- [Slim](https://marketplace.visualstudio.com/items?itemName=sianglim.slim): Slim language support based on https://github.com/slim-template/ruby-slim.tmbundle
- [Simple Ruby ERB](https://marketplace.visualstudio.com/items?itemName=vortizhe.simple-ruby-erb): Provides simple Ruby and ERB language, code snippets and ERB tag

## Configure ESlint path

- Press `ctrl(Command for Mac OSX) + comma` to open the vscode settings
- search for Eslint in the extensions tab 
- Click on `edit on settings.json` to open the settings.json file and put your home folder in the confiFile option  

```
"eslint.options": { 
	"configFile": "/Users/your_home_directory/.eslintrc.yml"
}
```
