![Flutter Community](https://raw.githubusercontent.com/fluttercommunity/community/master/welcome_banner.png)

# Flutter Community
**A central place for all community made Flutter packages.**

---

The Flutter Community is a GitHub organisation used to manage community made Flutter packages.

Our goal is to ensure packages made by the Flutter community are kept alive and maintained in one place.

## Medium Articles
To go along with the packages, we have started a Medium publication as a central location for community content to be published - especially if it relates to the packages here.

https://medium.com/flutter-community

# Submitting your packages
If you want your packages to be included in the Flutter Community organization, make sure you have read and completed the following steps.

<!--
## Guidelines
 - Android and iOS compatible
 - Package is published and approved on Dart pub.
 - ...
-->

## Preperation
In order for the Flutter Community organization to keep track of all the submitted packages and their maintainer, all repositories are required to contain a `COMMUNITY_INFO.yaml` file **in the root of the repository**. This file contains information about the package, pub page and maintainer.

**Note, without this file your package will not be listed in the [packages table](#Packages).**

### COMMUNITY_INFO.yaml
A `COMMUNITY_INFO.yaml` contains the following fields:
- `is_package: bool` - **REQUIRED**: This indicates if your repository is a package or not. This should almost always be `true`.
- `package_name: String` - *Optional*: The name of your package. If this field is not present, the name of the repository of your package will be used.
- `maintainer_name: String` - **STRONGLY RECOMMENDED**: The name of the current maintainer of the project (usually you).
- `maintainer_username: String` - **STRONGLY RECOMMENDED**: The maintainer's GitHub username.
- `package_description: String` - **STRONGLY RECOMMENDED**: A description of what your package does.
- `pub_package_name: String` - *Recommended*: The name of your package as listed on [Dart pub](https://pub.dartlang.org/). <br> Fill this in if the name of your package on [Dart pub](https://pub.dartlang.org/) is different to the name of your repository or the `package_name` in your `COMMUNITY_INFO.yaml`. <br> **When in doubt, leave empty.**

#### Example

Your `COMMUNITY_INFO.yaml` file should look something like this (example taken from [after_layout](https://github.com/fluttercommunity/flutter_after_layout)):
```yaml
is_package: true
package_name: after_layout
maintainer_name: Simon Lightfoot
maintainer_username: slightfoot
package_description: Brings functionality to execute code after the first layout of a widget has been performed.
pub_package_name: after_layout
```

## Getting in contact
If you've [prepared your packages](#preperation), you can either:
- **RECOMMENDED**: [Open an issue on the `community` repository.](https://github.com/fluttercommunity/community/issues/new)
- Contact us in the Flutter Study Group.
- Contact us through the Google Group https://groups.google.com/forum/#!forum/flutter-community or email the group flutter-community@googlegroups.com.

### Note to packages owners
This is only a branding change. The idea is to promote the integrity of packages. Not all packaged will be accepted.
