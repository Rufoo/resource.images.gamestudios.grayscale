# Game Studio Icons (grayscale)
Image resource set containing game studio icons/logos to be used in Kodi skins.

Credits & thanks:
* KiSUAN for the original icon set

## Contribute?
Have nice additions or fixes? You can contribute by using Git. Fork this [repository](https://github.com/chrisism/resource.images.gamestudios.grayscale) and add your stuff. 
Create a pull request to this original Git repository and I will review and pull if okay.  

Use NPM and install [kodi-addon-builder](https://github.com/chrisism/kodi-addon-builder) to build and package this project. Add the .addon file in the root of the project.  
Example contents:
```json
{
  "packagename": "resource.images.gamestudios.grayscale",
  "src": "./",
  "srcpaths": [
        "**/*.*",
        "!package.json"
  ],
  "dist": "./.dist/",
  "texturepaths": [
			"resource.images.gamestudios.grayscale/resources/Textures/"
  ],		
  "repositoryfolder": "./.dist/",
  "addonsdirectory": "%APPDATA%\\AppData\\Roaming\\Kodi\\addons",
  "semver": "",
  "host": "localhost",
  "port": "8080",
  "user": "kodi",
  "password": "kodi"
}
```

## Questions or issues
Use the github issues page for this project or follow the thread on the [Kodi forum](..).  
[Changelog](https://raw.githubusercontent.com/chrisism/resource.images.gamestudios.grayscale/master/changelog.txt)
