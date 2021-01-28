# LibTemplate
Android library template project.

Uses:

- [Timber](https://github.com/JakeWharton/timber)
- [view binding](https://developer.android.com/topic/libraries/view-binding)

Put all the documentation in the `app/doc` directory.
And leave images in in the `app/doc/images` directory.

# Rename both android studio project and library module

Edit your `settings.gradle` file and adjust the naming you wanna use for your project and library.
The current content looks like this: 

```
include ':MyLibrary'
include ':app'
rootProject.name = "LibTemplate"
```
