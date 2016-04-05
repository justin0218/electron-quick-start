# electron-quick-start

**Electron package issue windows**

I have an issue with the windows package when requireing libraries in the application. The linux package also works fine.

Steps to reproduce:
1. npm install
2. npm start  (works running on linux)
3. electron-packager . --all   (after installing the package manager globaly)
4. copy windows 32 package to windows 8 and run causes:
error "Cannot find module 'mssql'".

