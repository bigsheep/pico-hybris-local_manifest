The local manifests for building CM11 for HTC Explorer/Pico.

To sync:

    repo init -u git://github.com/mer-hybris/android.git -b hybris-11.0
    curl --create-dirs -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.github.com/bigsheep/pico-hybris-local_manifest/master/local_manifest.xml
    repo sync --fetch-submodules
    sh vendor/cm/get-prebuilts
