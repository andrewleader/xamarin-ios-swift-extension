# xamarin-ios-swift-extension
Microsoft.iOS / Xamairn.iOSwith Swift extension example project

### Handy tips for building this project

* Make sure your provisioning profile has an App Group
* When building the TestNativeApp in Xcode, follow the [instructions listed here](https://docs.microsoft.com/en-us/xamarin/ios/platform/ios14/) to _enable a project relative output location_.

### Instructions

1. Create the app identities for the app and the widget in App Store Connect
1. Create the app group in App Store Connect
1. If you chose different identities, update all the references in all the code
1. Open the SwiftExtension TestNativeApp project in XCode
1. In XCode, go to File -> Project Settings and change the first dropdown to "Project-relative Location" (the rest should be correct, click Done)
1. In XCode, build the project (Product -> Build)
1. In Terminal, `ls` to the directory of the .NET project, and execute `dotnet run -c Debug`, and it should build and launch the simulator and install and run!
1. Select the widget on the home screen.