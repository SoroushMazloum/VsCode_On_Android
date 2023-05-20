# VsCode_On_Android
## If you are a coder, you may like to use Visual Studio Code on android. In this way you can write codes in many languages like C++, C, C#, Python, Java, JavaScript... on your mobile phone.
-----------------------


### :gear: Get started

First of all you have to download 'Termux' application on you mobile phone. 
After downloading it first give it the permission to access your internal storage by typing the following command in Termux app.
```
termux-setup-storage
```
Then enter this command to install `proot-distro` and then install ubuntu with it:

```
pkg install proot-distro
```
```
proot-distro install ubuntu
```

After ubuntu is installed, login to it and update your packages

```
proot-distro login ubuntu
```
```
apt update
```

Now that your packages are up to date you can type the following command:

```
curl -fsSL https://code-server.dev/install.sh | bash
```

the above command will install code-server. To run it, type `code-server --auth none`.
Finally open your browser and in the search bar, search for `http://127.0.0.1:8080`

:green_book: Note
In some countries your need to turn on you VPN to install proot-distro or update your packages.

##  :heavy_check_mark: Installing Visual Studio Code using shell script
If you don't want to install Visual Studio Code manually, you can use the 'Installer' script. 
First install git:
```
apt install git
```
Clone the repository:
```
git clone https://github.com/SoroushGit/VsCode_On_Android
```
Go to it's directory:
```
cd VsCode_On_Android
```
Give the script permission to execute
```
chmod +x  Installer
```
Run it:
```
./Installer
```


# :heavy_exclamation_mark: Issues
If you have any problem, please send an Email to mazloomsoroush@gmail.com 
