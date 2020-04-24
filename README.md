# Instructions on How to Install Git

## Linux/Ubuntu

* Open ```Terminal```
* Run the command ```sudo apt-get update```
* Run the command ```sudo apt-get install git``` or ```sudo apt-get install git-core```
* Run ```git --version``` to check the version of git installed and verify installation

## GitHub CLI Installation

### macOS

`gh` is available via Homebrew and MacPorts.

#### Homebrew

Install: `brew install github/gh/gh`

Upgrade: `brew upgrade gh`

#### MacPorts

Install: `sudo port install gh`

Upgrade: `sudo port selfupdate && sudo port upgrade gh`

### Windows

`gh` is available via [scoop][], [Chocolatey][], and as downloadable MSI.

#### scoop

Install:

```
scoop bucket add github-gh https://github.com/cli/scoop-gh.git
scoop install gh
```

Upgrade: `scoop update gh`

#### Chocolatey

Install:

```
choco install gh
```

Upgrade:

```
choco upgrade gh
```

#### Signed MSI

MSI installers are available for download on the [releases page][].

### Debian/Ubuntu Linux

Install and upgrade:

1. Download the `.deb` file from the [releases page][]
2. `sudo apt install ./gh_*_linux_amd64.deb` install the downloaded file

### Fedora Linux

Install and upgrade:

1. Download the `.rpm` file from the [releases page][]
2. `sudo dnf install gh_*_linux_amd64.rpm` install the downloaded file

### Centos Linux

Install and upgrade:

1. Download the `.rpm` file from the [releases page][]
2. `sudo yum localinstall gh_*_linux_amd64.rpm` install the downloaded file

### openSUSE/SUSE Linux

Install and upgrade:

1. Download the `.rpm` file from the [releases page][]
2. `sudo zypper in gh_*_linux_amd64.rpm` install the downloaded file

### Arch Linux

Arch Linux users can install from the AUR: https://aur.archlinux.org/packages/github-cli/

```bash
$ yay -S github-cli
```

## Windows

* Right-Click on ```My Computer/This PC``` and Click on ```Properties```
* Check the architecture of your operating system (32 bit or 64 bit)
* Visit [Git SCM Windows](https://git-scm.com/download/win) and download ```Git for Windows Setup``` file (your download might automatically start) for your version of opearting system
* Double-Click the Setup file (.exe) and proceed with the installation
* Use all default settings/options while proceeding and **do not** change any settings 
* **Do not** install any existing software if prompted (Eg: Visual Studio Code)
* Open ```Command Prompt```
* Run ```git --version``` to check the version of git installed and verify installation

## Mac OS

* Visit [Git SCM Mac](https://git-scm.com/download/mac) and download ```Git for Mac Setup``` file (your download might automatically start). You should receive a file with ```.dmg``` or ```.pkg``` extension
* Double-Click the Installer file (.dmg) and proceed with the installation
* Use all default settings/options while proceeding and **do not** change any settings
* **Do not** install any existing software if prompted (Eg: Visual Studio Code)
* Open ```Terminal```
* Run ```git --version``` to check the version of git installed and verify installation

# Instructions for GitHub

* Visit [GitHub](https://github.com)
* Click on ```Sign Up``` and fill in relevant details
* **Note: Pick a username that represents you or that sounds professional. Remember that this is permanent and it is not recommended to change this**
* Be sure to remember your email that you have used, your username and password
