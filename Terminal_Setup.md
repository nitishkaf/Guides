# Terminal Setup with iTerm2 & powerlevel10k

This file provides a detailed guide for setting up your terminal with **[iTerm2](https://iterm2.com/)**, **[zsh](https://ohmyz.sh/)** and **[powerlevel10k](https://github.com/romkatv/powerlevel10k)**, including step-by-step instructions on how to install and configure both tools.

## Installation

First, Let's start by installing necessary tools.

- [iTerm2](https://iterm2.com)
- [zsh](https://www.zsh.org/):  Let's install zsh through our terminal.
    ```bash
        # using homebrew
        brew install zsh

        # using apt-get
        sudo apt-get install zsh
    ```
    Once you have installed **zsh**, it's time to install ***Oh my ZSH***

    Before installing, change `bash` to `zsh` in your terminal by typing `zsh` command.
    ```bash
        zsh
    ```
- [Oh my ZSH](https://ohmyz.sh/)

    To install, copy and paste this in your terminal.
    ```bash
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
    ```

Once you've installed ***iTerm2*** and ***Oh my ZSH***, you can then proceed with installing ***powerlevel10k***.

- [powerlevel10k](https://github.com/romkatv/powerlevel10k/)

    To install, copy and paste this in your terminal

    ```bash
    git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
    ```

## Enabling powerlevel10k

Once you have installed everything. It's time to enable powerlevel10k.

To enable it, we need to open `.zshrc` file and change the value of `ZSH_THEME`

To open `.zshrc` file in **VSCode**:
```bash
    code ~/.zshrc
```

Change the value of `ZSH_THEME`

```bash
    ZSH_THEME="powerlevel10k/powerlevel10k"
```

## Changing font

Make sure your terminal font is `FiraCode NF`, otherwise terminal will render characters instead of logos.

Install the font:
- [FiraCode NF](https://github.com/ryanoasis/nerd-fonts/raw/master/patched-fonts/FiraCode/Medium/complete/Fira%20Code%20Medium%20Nerd%20Font%20Complete.ttf)

Open your terminal settings and change the font to `FiraCode NF`

## Configuring Terminal

Now, that you have everything needed to create an amazing terminal.

type `p10k configure` in the terminal to open settings for powerlevel10k

```bash
    p10k configure
```

Follow the instructions to select the styles that you want for your terminal.


![Demo](https://res.cloudinary.com/practicaldev/image/fetch/s--71QSuVWr--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_66%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/xf9fk2sgux1niog4vhpy.gif)

