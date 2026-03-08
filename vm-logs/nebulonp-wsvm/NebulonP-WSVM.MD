## Homeone Test Lab - NebulonP-WSVM VM Log Folder Readme


### VM Function

NebulonP is a workstation VM named for its function which is to provide the tools required for learning and developing Python 3.

#### VM Change History

##### Initial Version:

The first version of this VM was created from a stock VM which had properly configured virtual hardware and a text-only version of Debian Trixie with the absolute minimum number of packages needed for booting and basic CLI functions. From this minimal staring point, the following steps were completed to get the VM to the needed state:

1. The following steps were completed in the initial stage of the VMs configuration:

    - kde-standard, terminator, info, make, automake, autoconf, git, binutils, parted, diffutils
        + These packages were installed along with any supporting -doc files.  This allowed the VM to be booted into the KDE GUI so a useful profile and layout could be configured for the Terminator terminal program, which would be very helpful in the following steps. 
    - python3.13, python3.13-doc, python3.13-examples, python3.13-dev, python3.13-dbg, python3.13-venv, python3-pip, geany, spyder, git-gui, git-flow, doc-base, dochelp
        + In this stage, Python3.13 and its associated packages and documentation were installed, as well as the Geany and Spyder integrated development environments and their associated plugins.  Finally, some additional packages to assist with git usage and reading & searching Debian package documentation.
    - Finally, a large number of python3- packages were installed, along with any associated -doc packages, that provide libraries of python functions that have been written to enhance the utility of the Python language and make it easier for developers to write python code which does whatever the specific library was designed to make easier.
 










#### VM Snapshot Listing