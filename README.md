# Tinder
Tinder Swag

# Demo 
https://www.youtube.com/watch?v=FTGa8Tjwfi8

# Launch Tinder
- Clone
- Npm install in terminal
- Run on IOS simulator or Android emulator

# Troubleshooting
## install react-native-cli
`npm install -g react-native-cli`
## upgrade react-native
`react-native upgrade`
## Make sure to have watchman istalled
`brew install watchman`
## Error “:CFBundleIdentifier”, Does Not Exist
https://stackoverflow.com/questions/37461703/print-entry-cfbundleidentifier-does-not-exist
## Error: ignoring return value of function declared with warn_unused_result attribute
Open Tinder.xcodeproj
project navigator -> Libraries -> RCTWebSocket.xcodeproj -> Build Settings -> search "Custom Compiler Flags" -> remove all flags

https://github.com/facebook/react-native/issues/8584
## Unrecognized font family 'Material Icons'
`react-native link react-native-vector-icons`
