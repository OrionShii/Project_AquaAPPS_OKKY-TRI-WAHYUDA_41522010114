**Aqua Mobile App**

Aqua is an Android-based mobile application that provides a variety of interactive and informative features related to Aqua services. The app is developed using Android Studio with Java and includes components such as user authentication, barcode scanning, and notifications.

**Features**
- User Authentication: Supports login and registration using email and Google Sign-In.
- Barcode Scanning: Integration with com.journeyapps.barcodescanner for barcode scanning.
- Notifications: Supports push notifications.
- Easy Navigation: Various activities handling different features within the app.
  
**System Requirements**
- Android Studio (latest version).
- Java Development Kit (JDK) version 8 or higher.
- Minimum SDK version 21.
- Google Firebase for authentication.
- Internet connection to download dependencies and communicate with Firebase.

**Installation**
Follow these steps to install and run the application locally:

**1. Clone the Repository**
```
git clone https://github.com/username/aqua-mobile-app.git
cd aqua-mobile-app
```

**2. Install Java SDK**
Ensure that you have the Java Development Kit (JDK) installed on your system. You can download it from the official Oracle website.

After downloading, follow the installation instructions for your operating system.

**3. Set Up Environment Variables**
After installing the JDK, set the JAVA_HOME environment variable and add the bin directory to your PATH.

**For Windows:**
- Open System Properties.
- Go to the Advanced tab and click on Environment Variables.
- Under System Variables, click New and add JAVA_HOME with the path to your JDK installation.
- Find the Path variable, click Edit, and add %JAVA_HOME%\bin.

**For macOS/Linux:**
Add the following lines to your ~/.bash_profile (or ~/.zshrc for zsh):
```
export JAVA_HOME=/path/to/your/jdk
export PATH=$JAVA_HOME/bin:$PATH
```

**4. Open in Android Studio**
- Open Android Studio.
- Select File > Open and navigate to the directory of the cloned project.

**5. Install Dependencies**
- Android Studio will automatically detect and download the necessary dependencies specified in the build.gradle files.

**6. Configure Firebase**
- Create a project in Firebase Console.
- Add an Android app to your Firebase project and download the google-services.json file.
- Place the google-services.json file in the app directory of your project.

**7. Run the Application**
- Connect your Android device or use an emulator.
- Click the Run button (play icon) in Android Studio to build and run the app.
