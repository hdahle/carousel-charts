# My first React Native app: carousel-charts
My goal was to create a React Native app with carousel/side-swipe style navigation and dynamic charts. 
I have a bunch of charts grouped in a handful of categories.
The plan was to swipe left/right to change categories, and to swipe up/down to view the charts in each category.

### Project dependencies

https://github.com/indiespirit/react-native-chart-kit

https://github.com/meliorence/react-native-snap-carousel

### How I got this thing working from scratch

My dev platform is Ubuntu 18.04 (actually WSL). 
I stumbled across https://docs.expo.io/ which turned out to be a super-nice development and testing framework for React Native.
I already had ````npm```` installed, so these are the steps required:

Install Expo:
````
npm install --global expo-cli
````
Create a 'Hello world' project template:
````
expo init carousel-charts
cd carousel-charts
````
Run the basic project:
````
expo start
````
This brings up a QR code - scan it with your mobile (which already has Expo Go installed, right?) and run the project. At this point, just keep the project running on the mobile device, it will update automatically as you edit code on your workstation.

Install dependencies for charts and for carousel navigation
````
expo install react-native-chart-kit
expo install react-native-svg
expo install react-native-snap-carousel
````
And that's it. Now just edit ````App.js```` and watch it update on the mobile device.

### Where to learn about Expo

https://docs.expo.io/

https://blog.expo.io/

### Where I learned about basic React Native

https://www.tutorialspoint.com/react_native/react_native_props.htm



