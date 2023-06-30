# VS-Code-on-Android
Running VS code on android devices and access the remote server.

## On Remote Linux Side Server
1. Go to [link](https://github.com/coder/code-server/releases) and download the `source code` zip file.
2. Download it and extract using
```
tar -xvf ./source file name.tar.gz
```
3. After extraction move into the `dir` and type
```
sh install.sh
```
3. After its built successfully, then from inside the `dir` where you installed it run `export PASSWORD="password"` set any password you want.
4. Then type `code-server`  it'll start VS Code on address `127.0.0.1:8080` on your linux machine.

## On Androind Device
1. Install termux from the given release `v0.1` or from F-Droid [link](https://github.com/termux/termux-app#Installation). Don't install it form Google Play Store.
2. Then run
```
termux-change-repo
```
3. Select the `Main` repo and then select mirror by `Tsinghua` or `Gimler`.
4. Install `Ubntu` on your android by following command
```
pkg install wget openssl-tool proot -y && hash -r && wget https://raw.githubusercontent.com/EXALAB/AnLinux-Resources/master/Scripts/Installer/Ubuntu/ubuntu.sh && bash ubuntu.sh
```
5. Start Ubnut by typing `./start-ubuntu.sh`

  
### check video for reference.

### References

https://www.codewithharry.com/blogpost/install-vs-code-in-android/

