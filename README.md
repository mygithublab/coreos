# coreos
1. Boot system from coreOS iso

2. sudo -i switch to root account

3. git config --global http.sslVerify false

4. cd~/

5. git clone URL which yaml file

6. cd ~/coreos/

7. coreos-install -d /dev/sda -c cloud-config.yaml

8. input "reboot" to restart system and apply cloud-config.yaml file
