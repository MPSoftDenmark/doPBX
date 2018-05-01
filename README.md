

## Pre-requisites
- A CentOS 7+ droplet (of any size)

####
## (A) Way to install
## Install a clean CentOS and then follow step 1-3

## Step 1: Get/Clone (if you have git) the script found in my GitHub Repository
- wget https://raw.githubusercontent.com/MPSoftDenmark/new-freepbx/master/install_freepbx.sh

## Step 2: Run the Script
- sh install_freepbx.sh

## Step 2.1: Configure mysql root with no password

## Step 2.2: Configure Asterisk modules

## Step 3: After the install-script finishup, browse to the FreePBX WebGUI using the IP address.


####
## (B) Way to install
## Install a CentOS using userdata from
- https://raw.githubusercontent.com/MPSoftDenmark/userdata/master/voip-newinst-centos?token=AZt4UH2ECz500FvnOMxfILGw63__urMZks5a8X94wA%3D%3D
