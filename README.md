# Serveo
Wrapper for serveo, makes it easier to use. Works on termux, and all versions of linux as long as they have ssh installed.
# Installation
## Dependencies
There are no dependencies for this project besides an ssh daemon. This can be accomplished by:
```
    sudo apt-get install ssh #remove sudo if on termux
```
## Linux
```
    git clone https://github.com/0xShaolin/serveo.git
    cd serveo
    sudo cp serveo /usr/bin && cp serveo /usr/local/bin 
```
## Termux
```
    git clone https://github.com/0xShaolin/serveo.git
    cd serveo
    cp serveo $HOME
 ``` 
# Usage
```
    serveo http <subdomain>
``` 
or
 
```
    serveo tcp <port>
```
or

```
    serveo kill
```

For termux, use bash before the respective commands
