
# Open Saber VR
Refer to other peoples forks for actual development. I created this fork to compile src and publish a working executable. I use Steam VR with Valve Index. Good luck for others wanting to use other platforms. Check out other forks. I don't plan on developing or supporting since I have no Unity experience

# Some notes for my future self.
## Compilation:
- Tag: checkout branch v0.1.3-dev
- Unity: compiled with 2018.4.34f1
- Platform: Windows 64bit
- Scenes: leave the scene order alone, will build as is. Don't change any settings

## Use BeatSyncConsole
```
{
  "BeatSyncConfigPath": "%CONFIG%\\BeatSync.json",
  "BeatSaberInstallLocations": [
    {
      "Enabled": false,
      "GameDirectory": "D:\\Program Files\\OpenSaberVR\\OpenSaberVR\\COMPILED"
    }
  ],
  "AlternateSongsPaths": [
    {
      "Enabled": true,
      "BasePath": "D:\\Program Files\\OpenSaberVR\\OpenSaberVR\\COMPILED\\Open Saber VR_Data",
      "SongsDirectory": "Playlists",
      "PlaylistDirectory": "Playlists_playlists",
      "HistoryPath": "BeatSyncHistory.json",
      "UnzipBeatmaps": true
    }
  ],
  "CloseWhenFinished": false,
  "UseSystemTemp": false,
  "ConsoleLogLevel": "Trace"
}
```
## Links
This is dead link, but credits go to devplayrepeat when it was around.
  [itch.io project page](https://devplayrepeat.itch.io/open-saber-vr)
