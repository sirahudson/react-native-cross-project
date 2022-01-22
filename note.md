react-native run-ios --simulator "iPhone XR" --verbose
simulator iPhone XR (ios version 12)

disable program in:

locate: 
~ ios/CrossProject/AppDelegate.m

locate : 
~ node_modules/react-native/React/Views/RCTDatePickerManager.m
~ node_modules/react-native/React/CoreModules/RCTAlertController.m

little configuration :
open Xcode -> preferences -> locations -> select most recent command line tools


react-native run-android

little configuration :
add path environment variable in .bash_profile

export ANDROID_HOME=/Users/friskiprad/Library/Android/sdk
export PATH=$ANDROID_HOME/tools:$PATH
export PATH=$ANDROID_HOME/platform-tools:$PATH

