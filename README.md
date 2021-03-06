
# react-native-secure-storage

## Getting started

`$ npm install react-native-secure-storage --save`

### Mostly automatic installation

`$ react-native link react-native-secure-storage`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-secure-storage` and add `RNSecureStorage.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNSecureStorage.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNSecureStoragePackage;` to the imports at the top of the file
  - Add `new RNSecureStoragePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-secure-storage'
  	project(':react-native-secure-storage').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-secure-storage/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-secure-storage')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNSecureStorage.sln` in `node_modules/react-native-secure-storage/windows/RNSecureStorage.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Com.Reactlibrary.RNSecureStorage;` to the usings at the top of the file
  - Add `new RNSecureStoragePackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNSecureStorage from 'react-native-secure-storage';

// TODO: What to do with the module?
RNSecureStorage;
```
  