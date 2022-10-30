Reading: React Native
=====================

Reading
-------

[getting started with react native](https://facebook.github.io/react-native/docs/getting-started)

1. Name three Core Components of React Native and describe what they do.

```code
   <View> , <Text> , <Image> , <ScrollView> , <Button> , and <TextInput>
```

2. What problem does React Native solve (why call it native)?
  for writing real, natively rendering mobile applications

3. What are the building blocks of a React Native app? How does that compare to a React app?
  Text and View are the two most basic building blocks of any React Native application.
  A part of the code can be written in Java for Android or Swift for iOS and integrated into React Native code. The global difference between React and React Native is that the former creates the DOM in a browser, while RN integrates into the architecture of Android and iOS-based mobile applications.

[expo](https://expo.io/)

1. What solution does expo provide?
    Expo aims to enhance React Native and provide all the JavaScript APIs you need for the most common needs.

2. Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the expo workflow.

3. What is the difference between React Native and Expo?
  The Expo client is a generic client that permits to load any app that is compatible with Expo. All the Expo apps do share the exact same native.

[expo snack](https://snack.expo.io/)

1. Checkout this tool. What does snack allow you to do?

[ejecting](https://docs.expo.io/versions/latest/expokit/eject)

1. What does “eject” mean within the context of Expo?
  When you eject from the managed workflow, the app becomes a vanilla React Native app that includes all the Expo SDK APIs that you were using.

2. When should you not eject?
    Once you eject expo, you can't inject it back. So, all the great development experience that you had with expo is gone now.

3. Why might you choose to eject?

  We call this "ejecting" because you still depend on the Expo SDK, but your project no longer lives inside Expo Go.

Tutorial
--------

[react native basics](https://facebook.github.io/react-native/docs/tutorial)

Bookmark and Review
-------------------

[react native](https://facebook.github.io/react-native/)