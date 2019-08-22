# react-native-samsung-iap-helper

## Getting started

`$ npm install react-native-samsung-iap-helper --save`

### Mostly automatic installation

`$ react-native link react-native-samsung-iap-helper`

### Manual installation


#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.svhawks.SamsungIapHelperPackage;` to the imports at the top of the file
  - Add `new SamsungIapHelperPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-samsung-iap-helper'
  	project(':react-native-samsung-iap-helper').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-samsung-iap-helper/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-samsung-iap-helper')
  	```


## Usage
```javascript
import SamsungIapHelper from 'react-native-samsung-iap-helper';

// TODO: What to do with the module?
SamsungIapHelper;
```
