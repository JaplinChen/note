##以管理者身份運行 CMD##
1. Windows+R 打開
2. 輸入 **runas /user:administrator cmd**
![runas.png](0)
3. 根據提示輸入密碼
![CMD input administrator password.png](1)

##Install Microsoft's **windows-build-tools**：##
```npm install --global --production windows-build-tools```
 from an elevated PowerShell or CMD.exe (run as Administrator).
npm config set msvs_version 2017
