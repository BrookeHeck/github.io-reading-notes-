# React Native

## Getting Started w/ React Native
1. Name three Core Components of React Native and describe 
what they do.
- view - the basic building block of a UI, a container that supports flexbox, style, some touch handling and accessibility controls
- Text - displays, styles, and nests strings of text and can handle touch events
- image - displays different types of images 

2. What problem does React Native solve (why call it native)?
- Android development uses Java and Kotlin to write views while iOS uses Swift or Objective-C
- With React Native, you can write all the components in JS and at runtime React Native creates the corresponding Android/iOS views for those components

3. What are the building blocks of a React Native app? How does that compare to a React app?
- The building blocks of a React Native app is the core components
- This is comparable to a React app because you must have one parent component and then nested components within

## expo
1. What solution does expo provide?
- framework that extends React Native
- developers can run and debug a new app with iOS and Android simulators on a browser or an actual device

2. Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.
- managed

3. What is the difference between React Native and Expo?
- React Native is a software library
- Expo is a framework and SDK that is used for testing and development

## expo snack
1. Checkout this tool. What does snack allow you to do?
- platform for running React Native apps in the browser
- When you want to share code, you can just send a link instead of someone having to download the code and setup the environment

## ejecting
1. What does “eject” mean within the context of Expo?
- it means that your project no longer inside Expo Go
- you will build and manage the app in Xcode and Android Studio

2. When should you not eject?
- if you want to distribute app to iTunes or Play Play
- you require push notification services
- if you want painless React Native upgrades that come with expo

3. Why might you choose to eject?
- when your expo project needs a native module that expo doesn't currently support

### Links
[getting started with react native](https://reactnative.dev/docs/getting-started)

[expo](https://expo.dev/)

[expo snack](https://snack.expo.dev/)

[ejecting](https://docs.expo.dev/expokit/eject/?redirected)

[react native basics - tutorial](https://reactnative.dev/docs/tutorial)

[react native](https://reactnative.dev/)