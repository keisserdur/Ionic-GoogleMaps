# Ionic-GoogleMaps

    $ > ionic start Map blank

    $ > cordova -v
        8.0.0
    
    $ > cordova platform list
        vailable platforms:
            android ~7.0.0
            browser ~5.0.1
            ios ~4.5.4
            osx ~4.0.1
            windows ~5.0.0
            www ^3.12.0
    
    $ > cordova plugin list
        No plugins added. Use `cordova plugin add <plugin>`.
        
    $ > npm install @ionic-native/google-maps @ionic-navite/core
    
    $ > cordova platform add ios
    $ > cordova platform add android
    $ > cordova platform add browser
    $ > cordova platform list
    
    $ > cordova platform list
        Installed platforms:
            android 7.0.0
            browser 5.0.4
            ios 4.5.5
        Available platforms:
            osx ~4.0.1
            windows ~5.0.0
            www ^3.12.0
            
    $ > ionic cordova plugin add cordova-plugin-googlemaps --variable API_KEY_FOR_ANDROID="AIzaSyApEuAuf2cvw_KYO6-6RmvX7cQaq1UAP1Y" --variable API_KEY_FOR_IOS="AIzaSyApEuAuf2cvw_KYO6-6RmvX7cQaq1UAP1Y"
    
    $ > sudo npm install --save @ionic-native/core@latest @ionic-native/google-maps@latest
    
    $ > ionic cordova run ios
        White page (not map)
    
    $ > ionic cordova build ios
