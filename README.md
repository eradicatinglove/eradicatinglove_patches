# eradicatinglove_patches
patches to load titles on hombrew


Signature Patches

Signature patches are created to be used alongside Atmosphere for loading certain homebrew from the home menu.
How to install Signature Patches

    Download the latest release.
        If you use fusee-primary.bin to boot into atmosphere, download fusee.zip.
        If you use fusee-secondary.bin to boot into atmosphere, download hekate.zip.
        If you're unsure on which release to get then check your hekate_ipl.ini file located in your /bootloader/ folder.
            If you have no such file, then get the fusee.zip release.
            If you see the following line payload=bootloader/payloads/fusee-primary.bin in your hekate_ipl.ini file, download fusee.zip.
            If you see the following line fss0=atmosphere/fusee-secondary.bin in your hekate_ipl.ini file, download hekate.zip.

    Unzip the release you've chosen into the root of your SD card.
        Make sure to click yes for overwriting any files and merging folders.
        Make sure the /atmosphere/ folder in the zip merges with the atmosphere folder on your SD card! You should not have an /atmosphere/atmosphere/ folder, nor should you have an /sd/, /fusee/, or /hekate/ folder on your SD card.

    Boot into atmosphere. You should now be using signature patches.
