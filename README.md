# 6 Degrees / Casual Critters Game

These two fully prototyped games are the result of 12 weeks of work from 12 students at BGNlab during the summer of 2017. The aim of these games was to see if player behaviour and attitude toward climate change could be influenced by video games, either casual or narrative-based.

## Install Instructions
1. Have Construct 2 (paid version only, as we use certain features unusable by free versions).
2. Open the 6Degrees.caproj in Construct 2
3. Enjoy.

## Build Instructions
1. Copy and paste either the Casual or Story app icons (depending on which game you want) into 6Degrees/Files, replacing the previous files.
2. Open Construct2
3. Go to the event sheet "GG Scores and Levels"
4. Set the global constant "GG_GAME_VERSION" to either "CASUAL" or "STORY", depending on which game you want to build.
5. Set the global constant "GG_DEBGU" to either 0 or 1, depending on if you want debug settings in your build.
6. Click on the project name (located at the top of the "Projects" pane) and look at the properties bar. Set the appropriate name, version, description, and ID.
7. Set the first layout to either "C6 Casual" for the casual game or "Opening" for the story game
8. Export the game to whichever platform you wish

### Exporting to Android
1. Select 'Cordova' as the platform to build for and build 
2. Compress the exported 'www' folder into a single 'zip' file
3. Go to build.phonegap.com, and sign up for an account, and go to the apps page. 
4. Upload the zip file. (As our game is larger than the size limit for free adobe accounts, you will need to have either a paid plan or an Adobe creative cloud membership)
5. Download the apk once it's done processing.
6. Plug in your android device of choice, and paste the apk into the device's storage. On the device's own file explorer you can find the apk and install it.

### Exporting for Web (and hosting on Github)
1. Select HTML5 as your platform when building.
2. Once finished, the specified directory will hold the necessary files needed to host the webpage for this game. You can host these files on any server you wish, otherwise, the following instructions will describe how to host it on Github servers.
3. Create a new repository of whatever name you wish the URL to contain. It can be either private or public.
4. Commit and push the files onto the repo.
5. In the repository settings under the 'Github Pages' section, make sure that the 'Source' is set to 'master branch' and save.
6. After a few minutes, the website should now be available at the following URL: [github username].github.io/[repository name]

[You can also see how to customize the domain name instead of username.github.io](https://help.github.com/articles/using-a-custom-domain-with-github-pages/)

It is important that you don't save, or at the very least, commit any build-setting related changes to the repository.
