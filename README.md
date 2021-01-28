# LibTemplate
Android library template project.

Uses:

- [Timber](https://github.com/JakeWharton/timber)
- [view binding](https://developer.android.com/topic/libraries/view-binding)

Put all the documentation in the `app/doc` directory.
And leave images in in the `app/doc/images` directory.

## Rename android studio project

Edit your `settings.gradle` file and adjust the naming you wanna use for your project.
The current content looks like this: 

```
include ':MyLibrary'
include ':app'
rootProject.name = "LibTemplate"
```
## Refactor the name of the library module
Using Android Studio refactor feature, rename the library module.

## Refactor the package name used in the library module
Again using Android Studio refactor feature, adjust the package name used by the library.
