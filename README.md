# AwesomeCI Demo React Native App

## Building and running locally

1. Run `yarn` to install the JS dependencies.
2. Run `yarn test` to run the JS tests (via `jest`).
3. Run `yarn start` to run the app in development mode. You can open it
   in the [Expo app](https://expo.io) on your phone. It will reload as
   you save edits to your files. You will see error messages and logs in
   your terminal window.

### Running the iOS app in the iOS simulator

This requires Xcode 9 or newer.

1. Run `bundle install` in the `ios` directory to install all
   dependencies.
2. Run `yarn run ios` to start the app in the iOS simulator.

You can also build the app directly by opening the iOS project in Xcode
and clicking **Product** -> **Run**.

To run tests, either select **Product** -> **Test** in Xcode, or run
`bundle exec fastlane test` in the command line inside the `ios`
directory.

### Running the Android app in the Android emulator.

1. Run `bundle install` in the `android` directory to install all
   dependencies.
2. Run `yarn run android` to start the app in the Android emulator.

To run tests, run `bundle exec fastlane test` in the command line inside
the `android` directory.

