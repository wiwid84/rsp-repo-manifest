# rsp-repo-manifest
RaspberryPi repo manifest

Quick start:
1. repo init -u https://github.com/wiwid84/rsp-repo-manifest.git -m rsp-manifest.xml --config-name
2. repo sync -c --no-clone-bundle
3. source setup
4. MACHINE=raspberrypi bitbake rpi-hwup-image
