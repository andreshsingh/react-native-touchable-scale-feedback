# react-native-touchable-scale-feedback
A (re)animated button with scale animation feedback. Animations work at 60fps even when js thread is busy.

![](example.gif)

## Installation
Using npm:
```
npm install --save react-native-touchable-scale-feedback
```
or using yarn:
```
yarn add react-native-touchable-scale-feedback
```

## Basic
| Prop           |     Default     |   Type   | Description                                                                                                 |
| :------------- | :-------------: | :------: | :---------------------------------------------------------------------------------------------------------- |
| onPress     |      ()=>{ }      |  `Function`  | Callback when the button is pressed |
| inactiveScale   |      1       |  `Number`  | The scale of the button when it is not pressed |
| activeScale |    0.9    | `Number` | The scale of the button when it is not pressed|

## Usage
```
import TouchableScaleFeedback from 'react-native-touchable-scale-feedback';

  ...
  <TouchableScaleFeedback
    activeScale={0.9}
    inactiveScale={1}
    onPress={()=>{console.log('Pressed')}}
  >
    // Your view here
  </TouchableScaleFeedback>
  ...
```
