
# Download StarUMLv6.2.2
[StarUML for Windows](https://staruml.io/api/download/releases-v6/StarUML%20Setup%206.2.2.exe)

[StarUML for Ubuntu](https://staruml.io/api/download/releases-v6/StarUML_6.2.2_amd64.deb)

[StarUML for Fedora](https://staruml.io/api/download/releases-v6/StarUML-6.2.2.x86_64.rpm)

# Quick activate on Linux
```py
    git clone https://github.com/dhoaibao/activate-StarUML-license.git
    sudo mv activate-StarUML-license/app.asar /opt/StarUML/resources
    rm -rf activate-StarUML-license/
```

# Manuly activate on Windows
1. Download **app.asar** file in this repository.
2. Replace **app.asar** file in the folder: ```C:\Program Files\StarUML\resources\```


# Check app.asar file if necessary:
1. Install **Node.js** and **npm**
2. Install **asar** via **npm**: ```npm i asar -g```
3. Extract source: ```asar extract app.asar app```
4. Check at ```app``` folder
5. Repackage app: ```asar pack app app.asar```
