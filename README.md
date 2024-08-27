# cordova-plugin-allow-backup
To allow you to set the debuggable property of a cordova-android application

```
<platform name="android">
    <edit-config file="AndroidManifest.xml"
                 target="/manifest/application"
                 mode="merge">
        <application android:debuggable="false"/>
    </edit-config>
</platform>
```

## Installation

By default adding this plugin to your cordova-android project will set the `android:debuggable` property in the `<application/>` tag to `false`.

```
cordova plugin add cordova-plugin-debuggable
```

If you want to set the property to `true` use the `debuggable` environment value.

```
cordova plugin add cordova-plugin-debuggable --variable debuggable=true
```
# cordova-plugin-debuggable
