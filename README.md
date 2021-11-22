# LinuxSetup
Necessary configuration FOR Linux configurations

### Basic packages. 
bashrc 
vim
anaconda

### .bashrc
Add terminal setup for default bash. 

### vim configuration
1. Download awesome vim packages to .vim_runtime. 
2. Update existing files with mine. 
3. Run install_awesome_vimrc.sh. 
4. Run python update_plugin.py
5. update Jedi-vim manually: git submodule update --recursive
Note that we may got import errors as jedi-vim depends on python-version and jedi module. 
Check the error message for the default python that is used. 
Install packages with default python with python -m pip install jedi. 

6. Problems: 
NerdCommenter does not work. Clone it manually. 


