# xibo-player-apptainer
Run the Xibo Windows client in an Apptainer image.

# What is in here?
The recipe file contains all the commands to build an image that will run Ubuntu 22.04 and install wine with all the necessary dependencies to run the xibo windows player.

# Usage
Install Apptainer with setuid
- apptainer build --sandbox xibo-player/ xibo-player.def # for testing
- apptainer build xibo-player.sif xibo-player.def # for productive

# Contribute
https://github.com/xibosignage/xibo-linux/issues/277
