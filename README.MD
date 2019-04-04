# mytTmetable -w- (IOS bundled)
* This version contains the offline bundle file for **myTimetable-w-** source.  
* This means this repo **don't contains** any react-native source in here.
* The main.bundle will be update when any new changes has made in to the main  **React native MyTimetable-w-** project
* An copy version of **package.json** is provided in there because you need it for your IOS build.
# How to build
1. Like other node js based project, you always run **npm install** or **yarn install** if you prefer yarn (like me) to get all the dependencies libraries that nedd for build this project.
2. After you done this step, you can build it though your xcode (like you build your normal ios project), open the xcode, and select the project under the **ios** folder.
3. Please ensure your build scheme in xcode is set to **Release** not **Debug** !!! because you don't want the development server jacked in to your app.
4. Also please remember to singing your own apple account in the project setting, because this will generate your own **Provisioning Profiles** and the **Signing Certificate** that you need for running on your real device, if you don't know how to do it, please refer this link: https://ioscodesigning.com/generating-code-signing-files/
5. After you done all the steps and checks above, you can hit the build button (or short cut **command + r**) to build the release version of the app.
6. if you want to build this app for your own ios device, please make sure you select the running target of your phone not the simulator.