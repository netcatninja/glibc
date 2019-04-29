BootStrap: docker
From: ubuntu:16.04

%help
    Start with a newer version of glibc. 

%runscript
    ldd --version | head -n 1
    
%environment
    export LANG=en_US.UTF-8
    export PATH=/usr/bin:/usr/local/sbin:/bin:/usr/local/bin:/usr/sbin:/sbin

%post
    apt-get -y update && apt-get install -y --no-install-recommends  \
    libc-bin 

%labels
    Author Brie Carranza
