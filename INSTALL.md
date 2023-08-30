### [Gnome Terminal](https://wiki.gnome.org/Apps/Terminal)

#### Install

This theme can be installed on Gnome 3 terminal and any other Gnome based terminal program like the Unity terminal bundled with Ubuntu.

You'll need the `dconf` command (if you run a recent Gnome version). In Ubuntu,this can be installed by running:

```bash
sudo apt-get install dconf-cli
```

In other distros you'll need to dig around to find it, search your repositories for **dconf** related packages.

After installing dconf, you can clone this repository to your machine.

```bash
git clone https://github.com/dracula/gnome-terminal
cd gnome-terminal
```

Then you can run the installation script:

```bash
./install.sh
```

And just follow the steps.

#### Addons

To complement your user experience I recommend installing [`zsh-syntax-highlighting`](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md). This is going to allow commands to have their own colors and styles.
