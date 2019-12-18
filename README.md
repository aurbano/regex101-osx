# [Regex101 OSX](https://aurbano.github.io/regex101-osx)
> Regex101 packaged as an offline Mac OSX application

![Regex101](https://raw.githubusercontent.com/aurbano/regex101-osx/master/assets/screenshot.png)

## [→ Download](https://github.com/aurbano/regex101-osx/raw/master/dist/Regex101.zip)

The app is basically the [offline version](https://github.com/Syskaw/Regex101.com-offline-app) of Regex101, packaged with [MacGap](https://github.com/MacGapProject/MacGap1) after adding some changes to it.

## Build

1. Install [MacGap](https://github.com/MacGapProject/MacGap1) 

   ```$ gem install macgap```

2. Build application:

    ```$ macgap build app --name Regex101 --output build```


The build script generates an application, available inside the `build` folder.

## Roadmap
Possible features to work on:

* Growl notifications (for timeouts for example)
* Update notifications (add a json file with the version and compare with the one on Github)
* Application icon
* Native top bar ([NSToolbar](https://github.com/MacGapProject/MacGap1/wiki/Add-NSToolbar-to-MacGap-application)) with the links in the we header.
* *Any ideas?*

------------

Original work by [@firasdib](https://github.com/firasdib), packaged as an application by [@aurbano](https://github.com/aurbano)
App released under the MIT License

[![Analytics](https://ga-beacon.appspot.com/UA-3181088-16/regex101-osx/readme)](https://github.com/aurbano)
