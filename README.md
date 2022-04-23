# About

This repository contains releases for the [Ultraworking](https://www.ultraworking.com) headquarters [app](https://www.ultraworking.com/download-headquarters). You may have been referred to this page if you are a Linux user and you can't use the [default instructions](https://www.ultraworking.com/download-headquarters) for MacOS or Windows.

# Installation

For Windows or MacOS, see the [instructions on the webpage](https://www.ultraworking.com/download-headquarters).

For Linux systems, navigate to the [releases](https://github.com/Ultraworking/headquarters/releases) page, and choose note the latest release version corresponding to your distributions's package manager.

For example, for Ubuntu, this would correspond to the .deb package. Then, install it with:

```
wget https://github.com/Ultraworking/headquarters/releases/download/v0.28.1/headquarters_0.28.1_amd64.deb
# sudo dpkg -i headquarters_0.28.1_amd64.deb
sudo apt install ./headquarters_0.28.1_amd64.deb
rm headquarters_0.28.1_amd64.deb

```

Note that this is a beta build, and as such, we make no guarantees of correctness, etc. This build also has to be updated manually

# To uninstall

```
sudo apt remove headquarters
# or dpkg --remove headquarters if you are using dpkg
```

# Roadmap

- [ ] Add auto-updating functionality to linux builds. Right now, headquarters has to be updated manually by users (e.g., by uninstalling and installing the latest build)

