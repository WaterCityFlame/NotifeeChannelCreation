# Notifee Channel Creation

This is a minimal reproduction of a bug reported to the notifee team where notification channels are not being created in release builds. 

To reproduce the issue, download this repo, run `npm install` and then run `npx react-native run-android variant=release`

The issue does not occur in Debug builds, so `npx react-native run-android` should get you a more functional app. 