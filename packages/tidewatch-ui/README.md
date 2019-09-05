# react-native-tidewatch-ui

## Getting started

`$ npm install react-native-tidewatch-ui --save`

### Mostly automatic installation

`$ react-native link react-native-tidewatch-ui`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-tidewatch-ui` and add `TidewatchUi.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libTidewatchUi.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.TidewatchUiPackage;` to the imports at the top of the file
  - Add `new TidewatchUiPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-tidewatch-ui'
  	project(':react-native-tidewatch-ui').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-tidewatch-ui/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-tidewatch-ui')
  	```


## Usage
```javascript
import TidewatchUi from 'react-native-tidewatch-ui';

// TODO: What to do with the module?
TidewatchUi;
```
