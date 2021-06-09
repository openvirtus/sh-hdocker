    Usage: hremote [OPTS...] [USER@HOST]
    
    This script helps mounting the local host's filesystem in a server. This
    enables the system administrator to write scripts easily. [Support hcfg]
    
    (i) Maybe you want to uncomment `user_allow_other` in /etc/fuse.conf in
        the server.
        > yum install epel-release --enablerepo=extras
        > yum install fuse-sshfs --enablerepo=extras --enablerepo=base
    (i) Install `vde2` to get `dpipe` in the local machine.
        https://github.com/virtualsquare/vde-2.git
    
    -v : Show environment variable.
    
    -m : Mount host to remote.
    -u : Umount host in the remote.
    
    -s : Open shell in the server.
## HDOCK-INSTALL

    Usage: hdock-install -vi
    
    This script helps installing the official docker.
    
    -v : Show configuration.
    -i : Install docker.
    -r : Remove /var/lib/docker/*.

## HDOCK-LS

    Usage: hdock-ls

## HDOCK-IMAGE-LS

List images.

    Usage: hdock-image-ls

## HDOCK-RM

    Usage: hdock-rm CONTAINER ...

## HDOCK-SH

    Usage: hdock-sh [OPT=VAL ...] [CONTAINER [COMMAND...]]
    
    -v         : Show variables.
    -q         : Execute without moving to current directory.
    -u USER    : Execute as user.
    -s SHELL   : Change default shell.
    -V         : Verbose output.

## HDOCK-COPY-SSH

    Usage: hdock-copy-ssh [-u USER] CONTAINER
    
    Install SSH keys into the docker.

## HDOCK-USERADD

    Usage: hdock-useradd CONTAINER [USER]
    
    Add user into the container.

## HDOCK-CREATE

    Usage: hdock-create [OPTS...] IMAGE CONTAINER [DOCKER-CREATE-OPTIONS...]
    
    Create a container with the following characteristics.
    
    1.- The used network is 'host'.
    2.- H:/dev/urandom <-> D:/dev/random
    3.- SYS_PTRACE capacity.
    4.- Unconfined.
    5.- It will execute 'sleep infinity'.

## DONATIONS
<ul>
<li>
<a href="https://openvirtus.github.io/files/1C1ZzDje7vHhF23mxqfcACE8QD4nqxywiV.png">[QR]</a>
<img height="20" style="max-height:1em;max-width:1em" src="https://openvirtus.github.io/files/btc.png">
Bitcoin <code>1C1ZzDje7vHhF23mxqfcACE8QD4nqxywiV</code>
</li>
<li>
<a href="https://openvirtus.github.io/files/bnb194ay2cy83jjp644hdz8vjgjxrj5nmmfkngfnul.png">[QR]</a>
<img height="20" style="max-height:1em;max-width:1em" src="https://openvirtus.github.io/files/bnb.svg">
Binance <code>bnb194ay2cy83jjp644hdz8vjgjxrj5nmmfkngfnul</code>
</li>
<li>
<a href="https://openvirtus.github.io/files/88JP1c94kDEbyddN4NGU574vwXHB6r3FqcFX9twmxBkGNSnf64c5wjE89YaRVUk7vBbdnecWSXJmRhFWUcLcXUTFJVddZti.png">[QR]</a>
<img height="20" style="max-height:1em;max-width:1em" src="https://openvirtus.github.io/files/xmr.svg">
Monero <code>88JP1c94kDEbyddN4NGU574vwXHB6r3FqcFX9twmxBkGNSnf64c5wjE89YaRVUk7vBbdnecWSXJmRhFWUcLcXUTFJVddZti</code>
</li>
</ul>
