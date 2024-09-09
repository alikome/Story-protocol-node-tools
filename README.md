# A tool for the Story Protocol Validators

What can this tool do:
Install the validator geth and consensus and create a "systemd" for both of them, in addition to
a update function that can install the latest versions when available and a few other shortcuts that can be used in 1 click.

# It can:

1 Install Story Node<br>
2 Update Story Node<br>
3 Create validator<br>
4 Get latest block height<br>
5 Get Validator dashboard link<br>
6 Get Validator Public and Private Keys<br>
7 Start the services<br>
8 Restart the services<br>
9 Stop the services<br>
0 Apply the latest Snapshot<br>
d Delete node

<p align="center">
  <img src="https://i.imgur.com/7Wdu7lZ.png" />
</p>

Note:  

1- This script must be run with root privileges<br>
2- This script is only for the linux-amd64-intel version

# How to:

    bash <(curl -s https://raw.githubusercontent.com/alikome/Story-Protocol-Node/main/storyTool.sh)

Or

    wget https://raw.githubusercontent.com/alikome/Story-Protocol-Node/main/storyTool.sh
    bash storyTools.sh

