# DreamHouse React Native Mobile App

React Native iOS implementation of the DreamHouse mobile app. DreamHouse is an end-to-end sample application that demonstrates how to build apps on the Salesforce platform. Visit the [DreamHouse Microsite](http://www.dreamhouseapp.io) for more information.

This version of the application is built with React Native and the Salesforce Mobile SDK, including some new [experimental features](https://github.com/ForceDotComLabs/react.force.datacontainer) to generate parts of the UI using Salesforce metadata.

This is an experimental project published under ForceDotComLabs, which means that:

1. It's work in progress
1. We need your feedback
1. Code contributions are welcome

![iOS Screenshot](/README_files/screen2.png?raw=true)  ![iOS Screenshot](/README_files/screen1.png?raw=true)

## TrailheaDX Presentation

Watch the recording of the presentation delivered at the TrailheaDX conference:

[![iOS Screenshot](tutorial_video/README_files/video2.png?raw=true)](https://www.youtube.com/watch?v=RY2vn2bT6XU)

## Installation Instructions

1. Follow [these instructions](http://dreamhouse-site.herokuapp.com/installation/) to install the Salesforce back-end.

1. Clone this repository:
    ```
    git clone https://github.com/ForceDotComLabs/dreamhouse-mobile-react
    ```

1. Navigate to the `dreamhouse-mobile-react` directory:
    ```
    cd dreamhouse-mobile-react
    ```

1. Install the npm dependencies:
    ```
    npm install
    ```

1. Install the cocoapods dependencies:
    ```
    pod install
    ```

    If the `pod` command is not found, install cocoapods first:
    ```
    sudo gem install cocoapods
    ```

    If the installation of cocoapods fails, you may need to upgrade the version of ruby installed on your system.


## Run in the iOS Emulator

1. Type the following command to open the project workspace in Xcode:
    ```
    open dreamhouse.xcworkspace
    ```

1. Start the development server:
  ```
  npm start
  ```

1. in Xcode, select a phone to emulate and click **Run**
