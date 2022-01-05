# Arch-Deployer
A script to bulk download an Arch Linux package with all its dependencies.

# Usage
1. Obtain the script, this can be done in multiple ways:
  
    - Using git (locally), eg. 

          git clone https://github.com/0xDEADCADE/Arch-Deployer
          chmod a+x ./arch-deployer ./arch-deployer-setup-chroot
     
2. Run the script by adding the name of the program (for example `$PROGRAM`), this way:

    - If downloaded locally with git
          
          ./arch-deployer $PROGRAM

At the end of the process, all the packages will be extracted and the folders placed into an .AppDir directory, so you can work on an AppImage.

# Related projects
##### Sources and tools
- libunionpreload from https://github.com/project-portable/libunionpreload
- appimagetool from https://github.com/AppImage/AppImageKit

##### This project is heavily inspired by
- pkg2appimage, at https://github.com/AppImage/pkg2appimage

# See also
"AM" the multi-architecture Application Manager for any GNU/Linux distribution, at

### https://github.com/ivan-hc/AM-application-manager
