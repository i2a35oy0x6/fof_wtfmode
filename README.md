# fof_wtfmode
 Fistful of Frags WTFMode
# Requirements
- SourceMod 1.10 or later
# Installation
Make sure your server has SourceMod installed. See Installing SourceMod. If you are new to managing SourceMod on a server be sure to read the 'Installing Plugins' section from the official SourceMod Wiki.

Download the latest release and copy the contents of addons to your server's addons directory.

It is recommended to restart your server after installing.

To confirm the plugin is installed correctly, on your server's console type:

sm plugins list

# Usage
- sm_wtfhelp
- !wtfhelp

# Compiling
If you are new to SourceMod development be sure to read the 'Compiling SourceMod Plugins' page from the official SourceMod Wiki.

You will need the spcomp compiler from the latest stable release of SourceMod. Download it from here and uncompress it to a folder. The compiler spcomp is located in addons/sourcemod/scripting/; you may wish to add this folder to your path.

Once you have SourceMod downloaded you can then compile using the included Makefile.

cd fof_wtfmode
make SPCOMP=/path/to/addons/sourcemod/scripting/spcomp
Other included Makefile targets that you may find useful for development:

# compile plugin with DEBUG enabled
make DEBUG=1

# pass additonal flags to spcomp
make SPFLAGS="-E -w207"

# install plugins and required files to local srcds install
make install SRCDS=/path/to/srcds

# uninstall plugins and required files from local srcds install
make uninstall SRCDS=/path/to/srcds

# License
GNU General Public License v3.0
