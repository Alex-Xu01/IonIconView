![IonIconView](https://raw.github.com/MarsVard/IonIconView/master/fancyad.png "the fancy ad")

Usage
=====

Add the repository and dependency to your project

Add this line to the root layout in your xml
```xml
xmlns:ioniconview="http://schemas.android.com/apk/res-auto"
```

now you can use iconviews and populate view the with any of [these](http://ionicons.com/) icons

```xml
<be.webelite.ion.IconView
  android:layout_width="wrap_content"
  android:layout_height="wrap_content"
  
  ioniconview:name="ion_ionic" <!-- this sets the icon -->
  android:textSize="40dp" <!-- this sets the icon size -->
  android:textColor="#ff0000" <!-- this sets the icon color -->
  />
```

Available Icons
=====
for a list of available icons please check out [ionicons.com](http://ionicons.com/)
ion-loading becomes ion_loading
ion-ionic becomes ion_ionic

Credits
=====
All credits go out to [ionicons.com](http://ionicons.com/)


Maven Repository
=====

Ready to use android library including rotating icons!

To use, add the following to your project's build.gradle file:

```gradle

repositories {
    maven { url 'https://raw.github.com/MarsVard/IonIconView/master' }
}

dependencies {
    compile 'be.webelite:ion-iconview:1.0.+@aar'
}

```

thanks to @Sonelli for explaining how maven works :)
