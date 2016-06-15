# comment
  - item
    * subitem
    * = notes
--------------------------------------------------------------------------------
# ConfFiles

# TODO
	- Create the installer for the vimrc in HOME
	- Test the installer for the bashrc in HOME

# References
		* http://vim.wikia.com/wiki/Example_vimrc
		
 --------------------------------------------------------------------------------
# FOLDER description
  - home
    * config files that goes on the $HOME directories
		@see NormalFiles

  - README.md
    * this file
--------------------------------------------------------------------------------
# For "installing" the normal files
	- Gives the file scrpit installer the execution permission,
		# chmod u+x script.sh
	- And run the damm thing
		# bash script.sh
	
# For "installing" the system config files
	- Gives the file scrpit installer the execution permission,
		# sudo chmod u+x script.sh || su -c "chmod u+x script.sh"
	- And run the damm thing
		# sudo bash script.sh || su -c "bash script.sh"

--------------------------------------------------------------------------------

# NormalFiles: those files do not require root permissions to be "installed"
# SysFiles: thos files do require some privilegies to be installed, like sudo, or su. If you don't have it ask for the system administrator to install them
		
