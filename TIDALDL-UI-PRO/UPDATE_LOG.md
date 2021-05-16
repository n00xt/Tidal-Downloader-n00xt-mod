#### v1.2.1.5
- [x] Fix: video path err
- [x] Add language: german

#### v1.2.1.4
- [x] Fix: download video
- [x] Fix: search

#### v1.2.1.3
- [x] Multi-language
- [x] Show DOLBY_ATMOS flag [A]
- [x] Search: turn page

#### v1.2.1.2
- [x] Auto update
- [x] Fix: download playlist
- [X] About-Page: show update-button when a new version released 

#### v1.2.1.1
- [x] Fix: download video
- [x] Show download speed
- [x] Login page: show proxy settings

#### v1.2.1.0
- [x] Use new-login-method
- [x] Fix: decrypt failed
- [x] Fix: long path problem

#### v1.2.0.6
- [x] Fix: replace track "title (version)" illegal characters 
- [x] Default AlbumFolderFormat: {ArtistName}/{Flag} [{AlbumID}] [{AlbumYear}] {AlbumTitle}
- [x] Settings: Video file format [#48](https://github.com/yaronzz/Tidal-Media-Downloader-PRO/issues/48)
- [x] Delete file if download err. [#40](https://github.com/yaronzz/Tidal-Media-Downloader-PRO/issues/40)

#### v1.2.0.5
- [x] Fix: download video(get stream) [#30](https://github.com/yaronzz/Tidal-Media-Downloader-PRO/issues/30)
- [x] Fix: album path end with "..." [#27](https://github.com/yaronzz/Tidal-Media-Downloader-PRO/issues/27)
- [x] Settings: Album folder format��Track file format [#33](https://github.com/yaronzz/Tidal-Media-Downloader-PRO/issues/33)
- [x] Version in filename [#32](https://github.com/yaronzz/Tidal-Media-Downloader-PRO/issues/32)

#### v1.2.0.4
- [x] Auto get the accessToken from tidal-desktop
- [x] Allow to cancel and retry download-task

#### v1.2.0.3
- [x] Show track-title contains version [#9](https://github.com/yaronzz/Tidal-Media-Downloader-PRO/issues/9)
- [x] Fix bug: the duration of the single tracks are always the duration of the album [#9](https://github.com/yaronzz/Tidal-Media-Downloader-PRO/issues/9)
- [x] Cover Hgih Resolution [#2](https://github.com/yaronzz/Tidal-Media-Downloader-PRO/issues/2)
- [x] Fix the display of the pop-up box
- [x] Encryption usersettings
- [x] Download playlist [#12](https://github.com/yaronzz/Tidal-Media-Downloader-PRO/issues/12)
- [x] Disc number [#17](https://github.com/yaronzz/Tidal-Media-Downloader-PRO/issues/17)

#### v1.2.0.2
- match userid when set accesstoken
- Skip uncheck-album when download artist's albums [#1](https://github.com/yaronzz/Tidal-Media-Downloader-PRO/issues/1)
- Fix allcheck button [#5](https://github.com/yaronzz/Tidal-Media-Downloader-PRO/issues/5)
- Fix typos across the app [#4](https://github.com/yaronzz/Tidal-Media-Downloader-PRO/issues/4)
- Save covers when downloding artist's albums [#7](https://github.com/yaronzz/Tidal-Media-Downloader-PRO/issues/7)
- Default download path: ./download/

#### v1.1.1.0
- Fix bug of login err(url_encode)
- Show track-codec when downloading
- Show audioModes on info-page
- Video-SetMetaData:Performers\Copyright\Title\Year #197
- Today is purple

#### v1.1.0.22
- Fix bug of long-file-path (settings MaxFileName) #353
- Fix bug of download video #343 #327
- Use another login method(from Redsea)
- Download Dolby Atmos(AC4 Codec\Low Quality\Mp4 format)
- Download SONY_360RA(MHA1 Codec\Low Quality\Mp4 format)
- Fixed the bug of Download-HIRES #347 #326
- Add AlbumID after album-folder-name (settings IDBeforeFolder)
- Add label [E] on search-page and info-page #264
- Add label [E] before albumtitle #264
- Volume to CD #265

#### v1.1.0.21
- Reduce the number of logins
- If one token is invalid, it is allowed to use only the other
- Fix bug of getTrack
- Add errmessage(convert mp4 to m4a failed) #288
- Check All/Uncheck All #248

#### v1.1.0.20
- Use CDN request
- Fix bug of getstream
- Modify settings-page
- Fix bug of long-file-path
- Add version after track-title

#### v1.1.0.19
- Fix bug of login(password is blank)
- Fix bug of settings-UseTrackNumber
- Add label [M] before albumtitle

#### v1.1.0.18
- Use cloud token

#### v1.1.0.17
- Update token

#### v1.1.0.16
- hide password
- Use track number(settings)
- Album\Artist Info page add column-quality 'M'

#### v1.1.0.15
- Fix bug of Multithreading-Download model
- Settings:  
1. AddYear
2. IncludeSingle
3. SaveCovers
4. AddExplicit

#### v1.1.0.14
- Fix bug of 'Asset is not ready for playback'

#### v1.1.0.13
- Update token

#### v1.1.0.12
- login by alias e-mail
- Search view add 'M'-Flag

#### v1.1.0.11
- Fix bug of download artwork
- Show errlabel when login err

#### v1.1.0.10
- Get ep&singles
- Check if song is downloaded already
- Fix bug of login

#### v1.1.0.9
- Name format 'atist-title.flac'
- Fix bug of download playlist
- Download by file: add artist��playlist

#### v1.1.0.8
- Search box: select all when double click 
- Settings: fixd bug, add search max num, add to chinese
- Fix bug of playlist video savepath

#### v1.1.0.7
- support http-proxy(login-page)
- Download playlist
- Tag: add composer

#### v1.1.0.6
- Fix bug of search
- Download by file
- Add search question button
- Select items which want to download
- Add setting of 'addhyphen'

#### v1.1.0.5
- Optimized search
- Fix bug of download
- Add serial number before file name
- Add setting of 'onlym4a'(convert mp4 to m4a)
- Check ffmpeg status
- Fix bug of set metadata
- Download by url
- Download artist albums
- Download album videos
- Modify ui  

#### v1.1.0.4
- Fix bug of metadata
