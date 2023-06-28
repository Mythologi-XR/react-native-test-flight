# react-native-test-flight

## Getting started

`$ yarn add @mythologi/react-native-testflight`

### Mostly automatic installation

`$ react-native link @mythologi/react-native-testflight`

### Manual installation

#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-test-flight` and add `RNTestFlight.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNTestFlight.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

## Usage

```javascript
import RNTestFlight from "@mythologi/react-native-testflight";

if (RNTestFlight.isTestFlight) {
  console.log("Ground control to Major Tom");
}
```
