# react-native-sms-verification-api
<!-- [![react-native version](https://img.shields.io/badge/react--native-0.41ee-0ba7d3.svg?style=flat-square)](https://github.com/facebook/react-native/releases/tag/v0.41.0)
![npm]()
[![npm (tag)]()]() -->

Verify your users by SMS without making them deal with verification code.


---

## Versions

| 1.x              | 
| ---------------- | 
| Android support  |
|    libraries     |


## Getting started

`$ yarn add react-native-sms-verification-api`

## Linking 

### >= 0.60

Autolinking will just do the job.

### < 0.60

### Mostly automatic installation

`$ react-native link react-native-sms-verification-api`

### Manual installation


#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.busfor.;` to the imports at the top of the file
  - Add `new ()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-sms-verification-api'
  	project(':react-native-sms-verification-api').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-sms-verification-api/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      implementation project(':react-native-sms-verification-api')
  	```

## Usage
```javascript
import SmsVerificationApi from 'react-native-sms-verification-api';

```
