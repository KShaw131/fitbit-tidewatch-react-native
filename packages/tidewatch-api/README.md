# react-native-tidewatch-api

## Getting started

`$ npm install react-native-tidewatch-api --save`

### Mostly automatic installation

`$ react-native link react-native-tidewatch-api`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-tidewatch-api` and add `TidewatchApi.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libTidewatchApi.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.TidewatchApiPackage;` to the imports at the top of the file
  - Add `new TidewatchApiPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-tidewatch-api'
  	project(':react-native-tidewatch-api').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-tidewatch-api/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-tidewatch-api')
  	```


## Usage
```javascript
import TidewatchApi from 'react-native-tidewatch-api';

// TODO: What to do with the module?
TidewatchApi;
```
