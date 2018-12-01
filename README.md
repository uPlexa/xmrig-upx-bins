# xmrig-upx-bins

[PROJECT MOVED TO HERE](https://github.com/uPlexa/xmrig-upx/)


XMRig-UPX is mining software for the uPlexa (cryptonight-upx) algorithm. This software utilizes a percentage of your CPU (adjustable by yourself) to mine uPlexa coins. This software is portable (does not install). Thus, if you wish to remove the software, simply remove the files (xmrig-upx directory).

Setup instructions:
------------------
CPU mining instructions:
Go through the airdrop process and get your public wallet key at www.uplexa.com(solutions to any problems with this process can be found in our Discord community)

Go back to uplexa.com and click on "Resources & Downloads" in the dropdown menu

Pick the xmrig download that suits your OS profile

Open the downloaded file in-

    (a) Windows

right click config.json

open with notepad(or any editor)

scroll to "user": "UPXwalletkey"

replace default address with yours

double check and save json file

double click start.bat file

     (b) Ubuntu/CentOS

Both platforms will require dependencies. Install them via:

Ububtu
------

``sudo apt-get install git build-essential cmake libuv1-dev libmicrohttpd-dev libssl-dev``

CentOS
------

sudo yum install -y epel-release

``sudo yum install -y git make cmake gcc gcc-c++ libstdc++-static libmicrohttpd-devel libuv-static``

Once installed, right click config.json

open with notepad(or any editor)

scroll to "user": "UPXwalletkey"

replace default address with yours

double check and save json file

run ``./xmrig``

Once you start mining, you can refer to back to the  "Resources and Downloads" page for the pool link (https://uplexa.poolbux.com). Insert your wallet key into the box at the bottom of the dashboard to track tour mining progress.

Refer back to the #mining channel in Discord for questions and configuration optimization.
