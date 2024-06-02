Aqua Mobile App
Aqua is an Android-based mobile application that provides a variety of interactive and informative features related to Aqua services. The app is developed using Android Studio with Java and includes components such as user authentication, barcode scanning, and notifications.

Features
User Authentication: Supports login and registration using email and Google Sign-In.
Barcode Scanning: Integration with com.journeyapps.barcodescanner for barcode scanning.
Notifications: Supports push notifications.
Easy Navigation: Various activities handling different features within the app.
System Requirements
Android Studio (latest version).
Java Development Kit (JDK) version 8 or higher.
Minimum SDK version 21.
Google Firebase for authentication.
Internet connection to download dependencies and communicate with Firebase.

Installation
Follow these steps to install and run the application locally:

1. Clone the Repository
sh
Copy code
git clone https://github.com/username/aqua-mobile-app.git
cd aqua-mobile-app
2. Install Java SDK
Ensure that you have the Java Development Kit (JDK) installed on your system. You can download it from the official Oracle website.

After downloading, follow the installation instructions for your operating system.

3. Set Up Environment Variables
After installing the JDK, set the JAVA_HOME environment variable and add the bin directory to your PATH.

For Windows:
Open System Properties.
Go to the Advanced tab and click on Environment Variables.
Under System Variables, click New and add JAVA_HOME with the path to your JDK installation.
Find the Path variable, click Edit, and add %JAVA_HOME%\bin.
