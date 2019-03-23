# Serveo
Wrapper for serveo, makes it easier to use. Works on termux, and all versions of linux as long as they have ssh installed.
# Installation
## Linux
    git clone https://github.com/0xShaolin/serveo.git
    cd serveo
    sudo mv serveo /usr/bin && mv serveo /usr/local/bin 
## Termux
    git clone https://github.com/0xShaolin/serveo.git
    cd serveo
    mv serveo /data/data/com.termux/files/usr/bin
    
# Usage
    serveo http <subdomain>
 
 or
 
    serveo tcp <port>

or

    serveo kill
