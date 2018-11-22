fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

# Available Actions
## Android
### android test
```
fastlane android test
```
Runs all the tests
### android beta
```
fastlane android beta
```
Submit a new Beta Build to Crashlytics Beta
### android deploy
```
fastlane android deploy
```
Deploy a new version to the Google Play
### android fetchMetadata
```
fastlane android fetchMetadata
```
Fetch all metadata of apps
### android blueberry
```
fastlane android blueberry
```
deploy each flavor
### android raspberry
```
fastlane android raspberry
```
deploy each flavor
### android strawberry
```
fastlane android strawberry
```
deploy each flavor
### android playstore
```
fastlane android playstore
```
Upload to playstore

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
