# libplex

libplex is an interface library to allow C programs to interact with PleX via
its REST API, as documented at
https://support.plex.tv/hc/en-us/articles/201638786-Plex-Media-Server-URL-Commands

# Getting Started

    # Clone the repo
    git clone https://github.com/davide125/libplex.git

    # Build it
    cd libplex
    ./autogen.sh
    make
    


Next, export environments variables with your plex username/password

    export PLEX_USERNAME=yourusername
    export PLEX_PASSWORD=yourpassword
    
Now, run it

    src/bin/plexq
