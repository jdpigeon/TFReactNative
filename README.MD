# TFReactNative Demo

Yes! Tensorflow can be integrated with React Native for Android!

In this proof-of-concept exercise, I recreated Omid Alemi's [Build Your First Tensorflow Android App](https://omid.al/posts/2017-02-20-Tutorial-Build-Your-First-Tensorflow-Android-App.html) tutorial in React Native.

Bridging to React Native was easy. I simply put all the Android Tensorflow functions into a Native Module Class.

Harder was making sure all the Tensorflow dependencies were included in the project correctly and playing nice with the rest of the app. I originally coded this using Tensorflow Android nightly [build #44](https://ci.tensorflow.org/view/Nightly/job/nightly-android/44/artifact/) and at the time of writing this the project is up to build # 195 :woah:
