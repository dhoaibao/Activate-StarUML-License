## Download StarUMLv6.2.2 x86_64
[StarUML for Windows](https://staruml.io/api/download/releases-v6/StarUML%20Setup%206.2.2.exe)

[StarUML for Ubuntu](https://staruml.io/api/download/releases-v6/StarUML_6.2.2_amd64.deb)

[StarUML for Fedora](https://staruml.io/api/download/releases-v6/StarUML-6.2.2.x86_64.rpm)

## Quick activation on Linux
```js
    git clone https://github.com/dhoaibao/Activate-StarUML-License.git
    sudo mv Activate-StarUML-License/app.asar /opt/StarUML/resources
    rm -rf Activate-StarUML-License/
```

## Manual activation on Windows
1. Download **app.asar** file at [here](https://github.com/dhoaibao/activate-StarUML-license/raw/main/app.asar).
2. Replace **app.asar** file in the folder: ```C:\Program Files\StarUML\resources\```

##
### Check app.asar file if necessary:
1. Install **Node.js** and **npm**
2. Install **asar** via **npm**: ```npm i asar -g```
3. Extract source: ```asar extract app.asar app```
4. Check at **app folder**
5. Repackage app: ```asar pack app app.asar```
##
**Source: [https://blog.csdn.net/mtrdong/article/details/133831497](https://blog.csdn.net/mtrdong/article/details/133831497)**
