Remix PA
===============

Thanks to ParanoidAndroid(AOSPA) !

We're open source, and patches are always welcome!


Getting Started
---------------

To get started with RemixPA, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the ParanoidAndroid trees, use a command like this:

    repo init -u git@github.com:RemixPA/manifest.git -b kk4.4

Then to sync up:

    repo sync

Get your working device tree that RemixPA already supported:

    . build/envsetup.sh
    getdevice {your-device-name}

then you can get a device tree and then

    lunch {your-device-name}

to get later work prepared.

Start build:

    ./mk {device}
or
    mka bacon    
