Free burger here --> https://github.com/rosneburgerworks/rosnebot-setup/blob/master/bot-profile.png

download nav meshes by doing ./update (doesnt install through install-catbots because of permission issues)

    cd Desktop
    
    git clone https://github.com/rosneburgerworks/rosnebot-setup.git; cd catbot-setup; ./install-catbots; ./update
    
Next you will have to edit the text document called accounts.txt in your catbot-setup folder and put the bots accounts in this format:

USERNAME:PASSWORD
USERNAME:PASSWORD
USERNAME:PASSWORD

## Required Dependencies
Ubuntu/Debian
`sudo apt-get install nodejs firejail net-tools x11-xserver-utils`

Fedora/Centos
`sudo dnf install nodejs firejail net-tools xorg-x11-server-utils`

Arch/Manjaro (High Support)
`sudo pacman -Syu nodejs npm firejail net-tools xorg-xhost`
