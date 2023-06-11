# Marvin Hsu's dotfiles  

This is my dotfiles repo, still a work in progress with more configurations to come. This repo uses dotter to manage dotfiles. [Dotter](https://github.com/SuperCuber/dotter) is a simple tool that helps you manage your dotfiles by creating symlinks from your home directory to your dotfiles repository.

## Usage

1. Clone this repo into `~/.dotfiles`  

    ```bash
    $ git clone https://github.com/marvin-hsu/dotfiles.git
    ```  

2. Change directory to `~/.dotfiles`  

    ```bash
    $ cd ~/.dotfiles
    ```  

3. Deploy the dotfiles using `Dotter`.  

    ```bash
    # If first time use Dotter, make it executable.
    $ chmod +x dotter

    # This repo includes the dotter executable for Linux.
    # Alternatively, use `cargo install` to get the latest release version.
    $ ./dotter deploy
    ```  

That's it! Your dotfiles should now be symlinked to your home directory.  