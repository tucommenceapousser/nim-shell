[![trhacknon](https://img.shields.io/badge/MadeBy-Trhacknon-yellow)
# Nim-Shell
<img src="https://github.com/tucommenceapousser/nim-shell/blob/main/nim.png">
Reverse shell that can bypass EDR and windows defender detection

# Please do not upload to VirusTotal

# 𝗜𝗡𝗦𝗧𝗔𝗟𝗟𝗔𝗧𝗜𝗢𝗡 𝗜𝗡𝗦𝗧𝗥𝗨𝗖𝗧𝗜𝗢𝗡𝗦
    $ apt install nim

# Compilation

# for windows
nim c -d:mingw --app:gui nimshell.nim


<img src="https://github.com/tucommenceapousser/nim-shell/blob/main/scwin.jpg">


# Compilation

## for linux:

nim c -d:mingw --app:gui nimshelllin.nim



<img src="https://github.com/tucommenceapousser/nim-shell/blob/main/sclin.jpg">

Change the IP address and port number you want to listen to in the nimshell.nim file according to your device.

<img src="https://github.com/emrekybs/nim-shell/blob/main/2.png">

# and listen

     $ nc -nvlp 4444
