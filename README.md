# VLC-Icecast-dir-fix
A patch for adding more stations for [Icecast Radio Directory](https://dir.xiph.org) in [VLC Media Player](https://www.videolan.org/vlc/). 

> [!NOTE]
> The patch file goes back to a VLC forum thread back in 2020, link: https://forum.videolan.org/viewtopic.php?p=514085. So I provided the working copy of the code (it is almost as it is in the forum but just changed the discriptor name in line 35 of the patch)

This patch adds a new section to the sidebar which shows all the other Radio Stations available to Icecast at the moment. 

For a template file on how this works in VLC, take a peek at [Gensokyo Radio config](./Playlists/Gensokyo-Radio.xspf) which was earlier available but not anymore, so it also works as a timepiece and memory which can be revived. To make it work, just drag and drop it into the Playlists section of VLC whenever you open it or just double-click it in the stored folder. 

# How to fix? 
For starters, just cut or copy the file inside **Patch** dir and paste it inside a specific folder in the installation directory of VLC Media Player. Directories for different OS are given below: 

1. **Windows**: `C:\Program Files (x86)\VideoLAN\VLC\lua\sd\`

Note that you will need Admin access to modify the directory. 

2. **Linux**: `/usr/share/vlc/lua/sd`
    - Note that you'd have to make the `sd` folder yourself via sudo.    

4. **MacOS**: `VLC.app/Contents/MacOS/share/lua/sd`

# Contribution

Feel free to add your own Radio Station files/Links too via. PR because once they are lost, it is quite hard to find another. So do it for the sake of information preservation. 
