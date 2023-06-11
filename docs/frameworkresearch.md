# Framework Research

Some aspects of the projects that need research on how to be built are what language to use that would allow cross operating system development, how to go about implementing the AI section of the project and how to create a workable user interface that people with less familiarity with technology could use.

## Languages

Some frameworks I know about are React Native, Xamarin and Flutter.

### Xamarin

Xamarin uses C# and . NET to create apps. This is good for apps on iOS and android and is free for individuals. It's not recommended for apps that demand heavy graphics however, which might cause an issue for this app as each platform has a different method for laying out screens.

### React Native

React Native uses Javascript and Typescript to create cross-platform apps. Up to 80% of the codebase can be shared across platforms, which would be useful in this context, however it isn't fully cross-platform, and some things such as a camera will need to be coded seperately. As the camera is a major part of this app, maybe React might not be the framework to use. However, React Native focuses on UI to a great extent, which would be useful for the app.

### Flutter

Flutter uses Dart. Developers have mentioned that Dart is 2x as fast as JavaScript, and is object-oriented. The way the app idea is working right now is not entirely object-oriented, so maybe Dart is not the language to use. Flutter however has a full set of widgets to help with UI implementation, however this causes app sizes to be larger.

### Cordova

Cordova uses CSS3, HTML5 for rendering and JS for logic. Since it uses web technologies (something i'm confident in), debugging will probably be easier. It also allows for the use of many libraries.
