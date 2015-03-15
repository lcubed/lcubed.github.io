---
layout:     post
title:      "ubuntu安装oh my zsh"
subtitle:   ""
category:   blog
date:       2015-03-15
author:     "L-Cubed"
---


1. Install zsh:

        $ sudo apt-get install zsh

2. Clone the repository:

        $ git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh

3. Optionally, backup your existing @~/.zshrc@ file:

        $ cp ~/.zshrc ~/.zshrc.orig

4. Create a new zsh configuration file:

        $ cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc

5. Change your default shell:

        $ chsh -s /bin/zsh

6. Reboot System:

        $ sudo reboot
