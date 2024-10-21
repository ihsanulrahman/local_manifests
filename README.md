To Initialize:
--------------

    git clone --depth=1 https://github.com/ihsanulrahman/local_manifests.git -b 14-volt .repo/local_manifests


To Sync:
--------

    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags

