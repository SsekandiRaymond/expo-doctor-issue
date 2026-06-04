```bash
RAYMOND@Raymond MINGW64 ~/New folder/expo-doctor-example (master)
$ npx expo-doctor --verbose
expo-doctor: v1.19.8
✔ Check for common project setup issues
✔ Check that local environment files are not committed
✔ Check package.json for common issues
✔ Check Expo config for common issues
✔ Check for overridden dependencies
✔ Check if the project meets version requirements for submission to app stores
✔ Check for lock file
✔ Check dependencies for packages that should not be installed directly
✔ Check for app config fields that may not be synced in a non-CNG project
✖ Check for issues with Metro config
✔ Check npm/yarn versions
✔ Check native tooling versions
✔ Check that packages match versions required by installed Expo SDK
✔ Check that native modules do not use incompatible support packages
✔ Check that required peer dependencies are installed
✔ Check Expo config (app.json/ app.config.js) schema
✔ Check for legacy global CLI installed locally
✔ Check that no duplicate dependencies are installed
✔ Validate packages against React Native Directory package metadata

18/19 checks passed. 1 checks failed. Possible issues detected:

✖ Check for issues with Metro config
It looks like that you are using a custom metro.config.js that does not extend "expo/metro-config". This can lead to unexpected and hard to debug issues. Learn more: https://docs.expo.dev/guides/customizing-metro/
Advice:
Update your "metro.config.js" to extend "expo/metro-config".

1 check failed, indicating possible issues with the project.


RAYMOND@Raymond MINGW64 ~/New folder/expo-doctor-example (main)
$ npx expo-env-info
Need to install the following packages:
expo-env-info@2.0.14
Ok to proceed? (y) 

  expo-env-info 2.0.14 environment info:
    System:
      OS: Windows 11 10.0.22621
    Binaries:
      Node: 24.15.0 - C:\Program Files\nodejs\node.EXE
      npm: 11.13.0 - C:\Program Files\nodejs\npm.CMD
    npmPackages:
      expo: ~55.0.26 => 55.0.26 
      react: 19.2.0 => 19.2.0 
      react-native: 0.83.6 => 0.83.6 
    Expo Workflow: managed
```
