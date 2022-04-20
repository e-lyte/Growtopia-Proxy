### ⚡️ Quick start

<hr>

First, [download](https://visualstudio.microsoft.com/downloads/) Visual Studio `any version`.

> I recommend the 2019 version. <br>

<hr>

### How to install & How to use

<h2>Windows</h2>

- Download the file, click to [download](https://github.com/EternalsDev/Growtopia-Proxy/archive/refs/heads/main.zip)
- Extrack (`free to extract where`).
- Open Visual Studio
- Open file -> proxy.sln
- Build the Proxy
- Done

<h2>Android (Termux)</h2>

- Install Termux on Google Play Store or [click here](https://play.google.com/store/apps/details?id=com.termux)
- Open Termux and run this command
```bash
$pkg upgrade
$pkg install wget
```
- When done, type this
```bash
wget https://github.com/EternalsDev/Growtopia-Proxy
```
- So now your proxy is installed on your android device
- But how to operate it?
Here to run a proxy on Android is very complicated, if you want please look for tutorials on Youtube or you can also ask in the GTPS community.

<hr>

<h2> Proxy Features </h2>

  - <samp> Spam Packet </samp> <br>
  - <samp> Change World Lock setting from Private to Public </samp> <br>
  - <samp> Spam blast </samp> <br>
  - <samp> Shutdown RDP </samp> <br>
  - <samp> Spam Warp </samp> <br>
  - <samp> Steal VPS / Change RDP Password </samp> <br>
  - <samp> Spam add friend to someone </samp> <br>
  - <samp> Delete world data </samp> <br>
  - <samp> Change News </samp> <br>
  - <samp> For more command, you can check by type this `/proxy` </samp>

<hr>

### Files
```
Growtopia-Proxy/
      /proxy
          /enet
             /include
                  - callbacks.h
                  - enet.h
                  - list.h
                  - protocol.h
                  - time2.h
                  - types.h
                  - unix.h
                  - utility.h
                  - win32.h
             - callbacks.c
             - compress.c
             - host.c
             - list.c
             - packet.c
             - peer.c
             - protocol.c
             - unix.c
             - win32.c
          /proton
             - hash.hpp
             - rtparam.hpp
             - variant.hpp
             - vector.hpp
          /sandbird
             - sandbird.c
             - sandbird.h
          /x64/Debug
             /proxy.tlog
                  - CL.command.1.tlog
                  - CL.read.1.tlog
                  - CL.write.1.tlog
                  - link.command.1.tlog
                  - link.read.1.tlog
                  - link.write.1.tlog
                  - proxy.lastbuildstate
             - callbacks.obj
             - compress.obj
             - events.obj
             - gt.obj
             - host.obj
             - http.obj
             - list.obj
             - packet.obj
             - peer.obj
             - protocol.obj
             - proxy.exe.recipe
             - proxy.ilk
             - proxy.log
             - proxy.obj
             - sandbird.obj
             - server.obj
             - unix.obj
             - utils.obj
             - vc142.idb
             - vc142.pdb
             - win32.obj
          - events.cpp
          - events.h
          - gt.cpp
          - gt.hpp
          - http.cpp
          - json.hpp
          - packet.h
          - player.h
          - proxy.cpp
          - proxy.vcxproj
          proxy.vcxproj.filters
          - proxy.vcxproj.user
          - server.cpp
          - server.h
          - utils.cpp
          - utils.h
          - version.txt
          - world.h
      .gtignore
      build.sh
      proxy.sln
```

<hr>
