fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios create_ios_app

```sh
[bundle exec] fastlane ios create_ios_app
```


The Fastfile stores the automation configuration that can be run with fastlane.
The Fastfile has to be inside your ./fastlane directory.
The Fastfile is used to configure fastlane. Open it in your favourite text editor, using Ruby syntax highlighting.


*** Specify the plaftform which targets to ex: ios/macos/tvos/watchos ***

*** Create/register app for both debug and release ***

*** Command for development: <fastlane create_ios_app --env debug> ***

*** Command for release: <fastlane create_ios_app --env release> ***

### ios signing_ios_app_debug

```sh
[bundle exec] fastlane ios signing_ios_app_debug
```

*** Create development certificate and provisioningProfiles ***

*** Command: <fastlane signing_ios_app_debug --env debug> ***

### ios signing_ios_app_release

```sh
[bundle exec] fastlane ios signing_ios_app_release
```

*** Create release certificate and provisioningProfiles ***

*** Command: <fastlane signing_ios_app_release --env release> ***

### ios generate_push_notification_profile

```sh
[bundle exec] fastlane ios generate_push_notification_profile
```

*** Generate push notifications related profiles ***

*** Command for debug: <fastlane generate_push_notification_profile --env debug>  ***

*** Command for release: <fastlane generate_push_notification_profile --env release>  ***

### ios get_profile_certs

```sh
[bundle exec] fastlane ios get_profile_certs
```

*** Get certificates for both develop and release ***

*** Command for debug: <fastlane get_profile_certs --env debug> ***

*** Command for release: <fastlane get_profile_certs --env release> ***

### ios match_ios_app_debug

```sh
[bundle exec] fastlane ios match_ios_app_debug
```

*** Update matching profiles and certificate in the project ***

*** Command for debug: <fastlane match_ios_app_debug --env debug> ***

### ios match_ios_app_release

```sh
[bundle exec] fastlane ios match_ios_app_release
```

*** Update matching profiles and certificate in the project ***

*** Command for release: <fastlane match_ios_app_release --env release> ***

### ios building_ios_app_debug

```sh
[bundle exec] fastlane ios building_ios_app_debug
```

*** Create Archive and .ipa file for debug ***

*** Command: <fastlane building_ios_app_debug --env debug> ***

### ios building_ios_app_release

```sh
[bundle exec] fastlane ios building_ios_app_release
```

*** Create Archive and .ipa file for release ***

*** Command: <fastlane building_ios_app_release --env release> ***

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
