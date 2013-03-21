Getting Started
---------------

To get started with PA-semc you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the PAC-man trees, use a command like this:

    repo init -u git://github.com/PA-semc/android.git -b cm-10.1

To sync up:

    repo sync

Then to build:

    ./build-pac.sh <device_name>
    example: ./rom-build.sh mango

