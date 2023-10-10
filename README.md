# Steps to configure zsh in new devices

* Install `brew` from [here](https://brew.sh/)
* Install zsh `brew install zsh`
* Install oh-my-zsh `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
* Install plugins
	* zsh-autosuggestions `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions` 
	* zsh-syntax-highlighting `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`
	* install powerlevel10k `git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k`
* Clone this repo
* Add symbolic link to `.zshrc` file `ln -s ~/path/to/repo/.zshrc ~/.zshrc`
* Add symbolic link to `.p10k.zsh` file `ln -s ~/path/to/repo/.p10k.zsh ~/.p10k.zsh`
* Restart terminal or `source ~/.zshrc` or `src` to apply changes

## Coming soon
* Add `install.sh` script to automate this process
