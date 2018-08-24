
# react-native-react-native-purchase

## Getting started

`$ npm install react-native-react-native-purchase --save`

### Mostly automatic installation

`$ react-native link react-native-react-native-purchase`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-react-native-purchase` and add `RNReactNativePurchase.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNReactNativePurchase.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNReactNativePurchasePackage;` to the imports at the top of the file
  - Add `new RNReactNativePurchasePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-react-native-purchase'
  	project(':react-native-react-native-purchase').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-react-native-purchase/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-react-native-purchase')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNReactNativePurchase.sln` in `node_modules/react-native-react-native-purchase/windows/RNReactNativePurchase.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using React.Native.Purchase.RNReactNativePurchase;` to the usings at the top of the file
  - Add `new RNReactNativePurchasePackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNReactNativePurchase from 'react-native-react-native-purchase';

// TODO: What to do with the module?
RNReactNativePurchase;
```
  