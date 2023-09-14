# Xcode
How to install xcode and commandline tools
### 1 . Xcode
--------------

1 . Open the App Store on your Mac.

2 . Search for "Xcode" in the search bar at the top right corner of the App Store window.

3 . Click on the "Get" button next to the Xcode app icon.

4 . Enter your Apple ID and password if prompted.

5 . Once the download is complete, Xcode will appear in your "Applications" folder.


![](https://github.com/ibasloom/Xcode/blob/main/Picture/xcode.png)


### 2 . Command Line Tools

--------------


### [To Download Command Line Tools](https://developer.apple.com/download/all/)


![](https://github.com/ibasloom/Xcode/blob/main/Picture/Commandline.png)


### 2 . CMD

--------------
![](https://github.com/ibasloom/Xcode/blob/main/Picture/CMD.png)

```
xcode-select --install
```

```
xcode-select -p
```

# How to Uninstall Xcode Command Line Tools
--------------
### 1 . Steps To Delete Xcode Command Line Tools
```
xcode-select -p
```

we will copy the path of that

![](https://github.com/ibasloom/Xcode/blob/main/Picture/CMD%20rm.png)
--------------
### 2 . Check How many file and folders are there
```
ls /Applications/Xcode.app/Contents/Developer
```

### 3 . now we will remove all this using this command
--------------
```
sudo rm -rf /Applications/Xcode.app/Contents/Developer
```
