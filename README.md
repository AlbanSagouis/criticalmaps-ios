# Critical Mass iOS App

> Critical Mass has been described as 'monthly political-protest rides', and characterized as being part of a social movement.
> 
> – [Wikipedia](http://en.wikipedia.org/wiki/Critical_Mass_(cycling))

This app helps all the critical mass participants to better organize the protest by tracking their location to share it with everyone else.

* __Website:__ http://criticalmaps.net
* __iTunes:__ https://itunes.apple.com/de/app/critical-mass-berlin/id918669647
* __Google Play:__ https://play.google.com/store/apps/details?id=de.stephanlindauer.criticalmaps
* __Android Project:__ https://github.com/CriticalMaps/criticalmaps-android

## Contribute

* Please report bugs with GitHub [issues](https://github.com/CriticalMaps/criticalmaps-ios/issues).
* If you can code please check the build & contribute guide below.
* If you have some coins left you can help to finance the server.


### How to build

	git clone REPO-URL
	cd criticalmaps-ios
	pod install
	open CriticalMaps.xcworkspace

__Important:__ While `pod install` you will be asked for _ParseApplicationId_ and _ParseClientKey_. You can enter a random key to make it build. To use the CriticalMaps network (Map and Chat) please contact us for working keys [info@pokuslabs.com](mailto:info@pokuslabs.com). To replace set keys take a look at [cocoapods-keys](https://github.com/orta/cocoapods-keys).

### How to contribute

1. Fork, then clone the repo:

        $ git clone REPO-URL

2. Create your feature branch:

        $ git checkout -b my-new-feature

3. Commit your changes:

        $ git commit -am 'Added some feature'

4. Push to the branch:

        $ git push origin my-new-feature

5. Submit a new [pull request](https://github.com/CriticalMaps/criticalmaps-ios/compare).

## Copyright & License

Copyright (c) 2014-2015 headione - Released under the [MIT license](https://github.com/criticalmaps/criticalmaps-ios/blob/master/LICENSE).
