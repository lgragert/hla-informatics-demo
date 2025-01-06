# MACOS SOFTWARE INSTALLATION GUIDE
Open MacOS Terminal program.

Copy and paste commands between backticks ``` (or grey boxes on GitHub webpage)


#### Make sure Xcode command line tools are installed

```
xcode-select --install
```



#### Homebrew: The missing package manager for MacOS (https://brew.sh/)

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

#### Curl - Downloads files from web / ftp

```
brew install curl
```



#### Install Additional Homebrew Repositories:

Bioinformatics repositories and way to update apps installed using cask

```
brew tap brewsci/bio
brew tap buo/cask-upgrade
```



#### Git - Source Control

```
brew install git
```



#### iTerm2 - alternative Mac terminal with more features:

```
brew install iterm2
```



#### Visual Studio Code Text Editor

```
brew install visual-studio-code
```



#### Python 3 Install

We're going to install the base Python distribution instead of Anaconda.

If you have Anaconda distribution already installed, things should still work.

```
brew install python3
```



#### BioPython module installs

Pip3 is the package manager for Python modules

```
pip3 install biopython
pip3 install scipy
pip3 install pandas
pip3 install py-ard
```

If you already have Anaconda installed, you can use `conda` instead of `pip3`



#### Jupyter Notebook to run Python code interactively

```
pip3 install jupyterlab
```



#### PyCharm - IDE for Python (optional)

```
brew install pycharm-ce
```



#### R and RStudio Integrated Development Environment (IDE)

```
brew install R
brew install rstudio
```



#### Try to Install Other Software Through Brew:

Lots of software packages can be installed and updated through Brew.

For example, you could try out Cursor - a version of VS Code with an AI assistant

```
brew install cursor
brew install inkscape
brew install obsidian
brew install skim
```


#### Clone the hla-informatics-demo Github repository:

Contains the scripts and toy datasets for my workshop

```
mkdir ~/dev/
cd ~/dev/
git clone https://github.com/lgragert/hla-informatics-demo.git
cd hla-informatics-demo
```
