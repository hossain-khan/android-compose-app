# Android - Circuit App Template
An Android App template that is preconfigured with Circuit UDF architecture.

> [!TIP]
> Google has an official template available. Have you checked it out yet?  
> https://github.com/android/architecture-templates

## What do you get in this template? 📜
* ✔️ [Circuit](https://github.com/slackhq/circuit) library setup for the app
* ✔️ Dependency Injection for all Circuit Screens & Presenter combo
* ✔️ Ktlint task in Gradle
* ✔️ GitHub actions

> [!WARNING]  
> _This template is only for Android app setup. If you are looking for a multi-platform supported template,_
> _look at the official [Circuit](https://github.com/slackhq/circuit) example apps included in the repository._

### Post-process after cloning 🧑‍🏭
Unfortunately, you do have to do some manual work after using the template, namely:

* [ ] Rename the package from **`app.example`** to your preferred app package name.
* [ ] Update directory structure based on package name update
* [ ] Update app name in XML and Gradle
* [ ] Update your app theme colors (_use [Theme Builder](https://material-foundation.github.io/material-theme-builder/)_)
* [ ] Generate your app icon (_use [Icon Kitchen](https://icon.kitchen/)_)
* [ ] Rename `ComposeApp***` to preferred file names
* [ ] Remove `Example***` files that were added to showcase example usage of app and Circuit.
