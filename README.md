
# react-native-xupdate

## Getting started

`$ npm install react-native-xupdate --save`

### Mostly automatic installation

`$ react-native link react-native-xupdate`

### Manual installation


#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.dou.xupdate.RNXupdatePackage;` to the imports at the top of the file
  - Add `new RNXupdatePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-xupdate'
  	project(':react-native-xupdate').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-xupdate/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-xupdate')
  	```


## Usage
```javascript
import RNXupdate from 'react-native-xupdate';

// TODO: What to do with the module?
RNXupdate;
```
  