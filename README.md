# React_Native__HelloWorld


1. Installing React Native
React Native is available as a Node.js package and can be quickly installed using npm, Node Package Manager.

	1. npm install -g react-native-cli
	To use React Native for developing Android apps, you should set the value of an environment variable called ANDROID_HOME to the absolute path of the directory containing the Android SDK. If you are using Bash shell, you can set the variable using export.

	1 export ANDROID_HOME=/path/to/Android/Sdk
	
	
2. Creating a New Project
To create a React Native project, you should use React Native’s command line interface or CLI, which can be accessed using the react-native command. We are creating a dictionary app in this tutorial so let’s call the project Dictionary.

	1. react-native init <react_native_project_name>
	Once the command completes, you will have a new directory called Dictionary, containing a starter React Native app. Enter the new directory using cd.

	1. cd react_native_project_name
	Before you proceed, I suggest you run the starter app to make sure that your development environment has everything React Native needs. To do so, type in the following command:

	1. react-native run-android
	You will now find an app called Dictionary installed on your emulator. Click on its icon to start it. If everything went well, you should see a screen that looks like this: