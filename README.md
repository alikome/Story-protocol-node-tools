# A tool for the Story Protocol Validators

What can this tool do:
Install the validator geth and consensus and create a "systemd" for both of them, in addition to
a update function that can install the latest versions when available and a few other shortcuts that can be used in 1 click.

# It can:

1 Install Story Node<br>
2 Update Story Consesus<br>
3 Update Story Geth<br>
4 Create validator<br>
5 Get latest block height<br>
6 Get Validator dashboard link<br>
7 Get Validator Public and Private Keys<br>
8 Start the services<br>
9 Restart the services<br>
0 Stop the services<br>
s Apply the latest Snapshot<br>
d Delete node, This step is irreversible<br>
q Quit

<p align="center">
  <img src="https://i.imgur.com/przWz74.png" />
</p>

Note:  

1- This script must be run with root privileges<br>
2- This script is only for the linux-amd64-intel version

# How to:

    bash <(curl -s https://raw.githubusercontent.com/alikome/Story-Protocol-Node/main/storyTool.sh)

Or

    wget https://raw.githubusercontent.com/alikome/Story-Protocol-Node/main/storyTool.sh
    bash storyTools.sh

