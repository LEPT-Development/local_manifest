Local_Manifest
==============

Manifest for building cm12.1 for c50


How to build:
-------------

Initializing a Build Environment:

    https://source.android.com/source/initializing.html

Initialize repo:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-12.1

    curl --create-dirs -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.githubusercontent.com/lept-development/local_manifest/master/local_manifest.xml
    repo sync

Compile:

    . build/envsetup.sh
    brunch c50
