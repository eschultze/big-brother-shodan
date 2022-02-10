# big-brother-shodan
Discover cameras running the RTSP protocol with live image and audio from all over the world

How to run?
```
./big_brother_shodan.sh
```
or search by country code with 2 letters such as US, RU, BR, MX, etc.
```
./big_brother_shodan.sh us
```

Must have:
* Shodan account with working [CLI](https://help.shodan.io/command-line-interface/0-installation) and API key
* curl
* gzip
* ffmpeg
* [VLC](https://www.videolan.org/)

Once it's done you'll have a .m3u list to open with VLC and several screenshots saved in the snapshots folder.

![image](https://user-images.githubusercontent.com/12034548/153490600-27295196-df4c-49e5-befd-3e8844f7c922.png)
![image](https://user-images.githubusercontent.com/12034548/153491050-27f5acbf-1d20-4874-ade4-30c7e55fe57e.png)
![image](https://user-images.githubusercontent.com/12034548/153492591-d4ac81f6-aee5-4b21-942d-5676ff55f53a.png)
