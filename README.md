# Video Chat code sample for React Native for ConnectyCube platform

This README introduces [ConnectyCube](https://connectycube.com) Video Chat code sample for React Native

Project contains the following features implemented:

- User authorization
- Group video calls (up to 4 users)
- Mute/unmute microphone
- Switch cameras

## Documentation

ConnectyCube React Native getting started - [https://developers.connectycube.com/reactnative](https://developers.connectycube.com/reactnative)

ConnectyCube Video Chat API documentation - [https://developers.connectycube.com/reactnative/videocalling](https://developers.connectycube.com/reactnative/videocalling)

## Screenshots


## Quick start and develop


## Build your own VideoChat app

To make the sample works for your own app, please do the following:

1.  Register new account and application at `https://admin.connectycube.com` and then put Application credentials from 'Overview' page into `src/config.js` file:

    ```javascript
    export const credentials = {
      appId: 0,
      authKey: "",
      authSecret: ""
    };
    ```

2.  At `https://admin.connectycube.com`, create from 2 to 4 users in 'Users' module and put them into `src/config.js` file:

    ```javascript
    export const users = [
      {
        id: 1,
        name: "User1",
        login: "videouser1",
        password: "videouser1",
        color: "#34ad86"
      },
      {
        id: 2,
        name: "User2",
        login: "videouser2",
        password: "videouser2",
        color: "#077988"
      },
      {
        id: 3,
        name: "User3",
        login: "videouser3",
        password: "videouser3",
        color: "#13aaae"
      },
      {
        id: 4,
        name: "User4",
        login: "videouser4",
        password: "videouser4",
        color: "#056a96"
      }
    ];
    ```

3. Install node modules - `npm install`
4. Run `react-native run-ios` or `react-native run-android`.
