# "epkg" Package Manager

**epkg** is a package manager, which is a source-based package manager using 7 reliable mirrors. 
You can install **epkg** package manager on any Linux based system with:
- wget
- sed
- awk
- make
- ./configure
- gcc
- g++

### How to Install epkg Package Manager to Your Linux Based System

- Before installing epkg, you need to have the programs listed above.
- After you made sure your Linux based system has these programs, run this command:

**git clone https://github.com/ENux-Distro/epkg.git**

**sudo cp epkg /usr/bin/epkg**

**sudo chmod 755 /usr/local/bin/epkg**
 - Ensure the package manager is installed succesfully, by installing a simple package like nano with:

**sudo epkg install nano**

And voila. You have installed **epkg** on your Linux based system.
If you want a distribution with this package manager pre-installed, you should try out [EPkgOS](https://github.com/ENux-Distro/EPkgOS)
