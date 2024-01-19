
# StarUML
Download: [StarUML](https://staruml.io/download/)

# Activate the StarUML license on Windows
1. Open **Command Prompt (Run as administrator)**
2. Install **asar** via **npm**: ```npm i asar -g```
3. Extract source
   
   ```cd C:\Program Files\StarUML\resources```
   
   ```asar extract app.asar app```
5. Edit **license-manager.js**

   Open **Visual Studio Code** to the path ```C:\Program Files\StarUML\resources\app\src\engine\license-manager.js```:

   > Change this

   ```py
    checkLicenseValidity () {
        this.validate().then(() => {
          setStatus(this, true)
        }, () => {
        //===> Cambiar false por true
          setStatus(this, true)
          //===> Comentar Dialog
          // UnregisteredDialog.showDialog()
        })
      }
    ```
   > **Ctrl + S -> Retry as Administrator**

5. Repackage app: ```asar pack app app.asar```
6. Open **StarUML**, **Help -> Enter License Key**: ```"You already have a valid license."```. Successful activation!
   
# Activate the StarUML license on Ubuntu
1. Open **Terminal**
2. Install **asar** via **npm**: ```sudo npm i asar -g```
3. Extract source
   
   ```cd /opt/StarUML/resources/```
   
   ```sudo asar extract app.asar app```
5. Edit **license-manager.js**
   ```sudo <text_editor> app/src/engine/license-manager.js```

   > Change this
   
    ```py
    checkLicenseValidity () {
        this.validate().then(() => {
          setStatus(this, true)
        }, () => {
        //===> Cambiar false por true
          setStatus(this, true)
          //===> Comentar Dialog
          // UnregisteredDialog.showDialog()
        })
      }
    ```
7. Repackage app:
   ```sudo asar pack app app.asar```
8. Open **StarUML**, **Help -> Enter License Key**: ```"You already have a valid license."```. Successful activation!

### Source: [StarUml 3.](https://gist.github.com/jjvillavicencio/4e3615a8219bb1a17c81c4541c6c317d) and [Get full version of StarUML](https://gist.github.com/trandaison/40b1d83618ae8e3d2da59df8c395093a)
