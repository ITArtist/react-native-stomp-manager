# react-native-stomp-manager

## Getting started

`$ npm install react-native-stomp-manager --save`

### Mostly automatic installation

`$ react-native link react-native-stomp-manager`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-stomp-manager` and add `StompManager.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libStompManager.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.StompManagerPackage;` to the imports at the top of the file
  - Add `new StompManagerPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-stomp-manager'
  	project(':react-native-stomp-manager').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-stomp-manager/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-stomp-manager')
  	```


## Usage
```javascript
import StompManager from 'react-native-stomp-manager';

// TODO: What to do with the module?
StompManager;
```
