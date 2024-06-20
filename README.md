# MUNI-OS: Jammy Edition
An extended Ubuntu version with some useful additions for every user.

Hello there, welcome to the home of MUNI OS.
MUNI OS "Jammy" is a Ubuntu Linux with some software additions that are useful for every user, It was made based on Ubuntu "Jammy" using penguins-eggs software (https://github.com/pieroproietti/penguins-eggs/) to remaster it and add everything.

Penguins-eggs software is conserved trough installations so you can add your modifications too for make it your own and repicate your system at will, or use it to make a backup of your custom system.
Some of the software added:


·Linux Xanmod Kernel (for the latest and greatest), the kernel supplied by Ubuntu is preserved for allowing SecureBoot installations and better compatibility with hardware.

·ClamAV Antivirus Software (for extended security), is integraded with "Linux Malware Detect" (LMD) and Nautilus file manager, and also installed rkhunter and chkrootkit for extended rootkit detection and protection.

·Latest Libreoffice release for documents and Gedit for advanced text edition.

·Latest Firefox stable from its repo, instead of the Snap package version.

·"ubuntu-restricted" addons and extras added for every codec and multimedia support.

·deb-get package manager, for extended software repository support.

·Snap package and Flatpak package support added (With flathub enabled).

·Pacstall installed, for even more software repository support.

·quickemu, one of the best software for work with VMs, and Virtual Machine Manager for complete VM managing.

·distrobox (trough pacstall, for the latest version), for the absolute software support trough easily managed containers.

·Eog (Eye of Gnome) and Shotwell for image view and gallery, GIMP for professional image editing.

·Brasero, .iso file managing and disc burning suite.

·Spotify from its repository.

·Whatsapp For Linux, Rustdesk (one of the best remote desktop software), YouTube Music, Discord and Zoom (trough deb-get)

·Teamviewer from its package, for even broader Remote Desktop support and assist.

·Onedriver and MegaSync for cloud drive and sync support

·scrcpy and Gsconect for mobile devices integration

·Timeshift, for backup and restore support for the system

·Gparted whith additional packages for the ultimate partition managing, and also installed partimage for additional partition backup/imaging support

·Audacity for professional audio editing and producing

·Gdebi for easy manual installations of packages

·VLC for the ultimate audio and video player

·MKVtoolnix GUI, for dealing with mkv video files

·GRUB Customizer for editing and customize your bootloader experience

·Gnome System Tools, for additional user management support

·USBview, utility for getting additional info about your usb conected devices

·Gnome Extension manager, also installed "user-themes" and "impatience" extensions

·Penguins-Eggs, for self-replicant function and backup/restore support for the system

·Additional packages and libraries for all the mentioned software


# Users: oem
# Password: oem
# Root password: oem

# Installation Instructions

MUNI OS "Jammy" installation process has two phases:

·Boot into live session and install with GUI installer Calamares as normally, with the detail to create and user called: "oem", with a password you can easily remember for the next phase of the installation

·Reboot, now you are booted and enter a session of your system with the newly created "oem" user, you can make more customizations to your system in this session if you want; and when you finish you have to proceed to navigate the applications and open: 
 "Prepare for shipping to end user" one, it will ask for the password you setup for the user "oem", it will proceed to delete the "oem" user and its data, and finally ask you to reboot.

After that you will be booted in a "First User set-up session" of Gnome-Shell where you can configure a personal or final user thats going to use the system.


MUNI-OS: Jammy, an extended, self-replicant, easy to deploy Ubuntu version with useful additions for every user.
