# Chromatic

[![](https://jitpack.io/v/calintat/chromatic.svg)](https://jitpack.io/#calintat/alps)

Get quick access to all Material Design colors in both Java and XML.

How to use
----------

Add the JitPack maven repository to the list of repositories:

```gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```

Add the dependency to the gradle build file:

```gradle
dependencies {
    compile 'com.github.calintat:colorful:1.0.1'
}
```

Now you have access to the entire Material Design color palette:

```java
coordinatorLayout.setStatusBarColor(Colorful.blue700);
```

```xml
<style name="AppTheme" parent="Theme.AppCompat.Light.DarkActionBar">
    <item name="colorPrimary">@color/blue_500</item>
    <item name="colorPrimaryDark">@color/blue_700</item>
    <item name="colorAccent">@color/yellow_A200</item>
</style>
```