## Environment variables

#### on macOS/on Linux distributions

- Set **JAVA_HOME**  
```echo export "JAVA_HOME=\$(/usr/libexec/java_home)" >> ~/.bash_profile```

- Set **ANDROID_HOME**  
```export ANDROID_HOME=/Users/<Your UserName>/Library/Android/sdk```  

  Update the Path with your **UserName**

- Set **PATH** variables  
```export PATH=${PATH}:$ANDROID_HOME/tools:$ANDROID_HOME/build-tools/<Android Version>:$ANDROID_HOME/platform-tools:$ANDROID_HOME/tools/bin:$ANDROID_HOME/emulator:$JAVA_HOME/bin```

  Update the Path with your **Android Version**


#### on Windows

- Set **JAVA_HOME**
 
  - Search for **Advanced settings**   
  - Click the **Advanced tab**, then click the **Environment Variables** button.  
  - Under **System Variables**, click New.  
  - Enter the variable name as **JAVA_HOME**.  
  - Enter the variable value as the **installation path** for the Java Development Kit.  
  - Click **OK**.  
  - Click **Apply Changes**. 

  ![alt text](https://i.imgur.com/P6NQyrz.jpg)
  

  
- Set **ANDROID_HOME**  

  ![alt text](https://i.imgur.com/S8Qiu5i.png)
  

## Connect device In USB debugging mode
 You need to connect real android device with PC in USB debugging mode in order to run android app automation tests in real android device using appium.
   ### Enable Developer Option
   To enable **Developer Option** in android device
  - Go to **Settings**.
  - Scroll down to bottom and tap on **About Phone**.
  - Scroll down bottom again on About Phone screen. You will see option **Build number**.
  - Tap on **Build number** option one by one until tt will show you message **"You are now a developer!"**. 
  - Now go back to **Settings** and scroll **down bottom**.

You will see option **Developer Options** above About Phone.
  
 ### To start USB Debugging mode
 Connect your device with PC using USB cable.  
  - Go to **Settings -> Developer options**.
  - There will be option **USB debugging** with check box. **Check it**.  
  - It will ask you to **"Allow USB debugging?"**. Tap on **OK**.  
 
 It will **enable USB debugging mode** for your android device.
  
  ### Verify Device Connected Properly With PC
  To verify device is connected properly with PC with USB debugging mode,
   - Open **command prompt** in your PC.
   - Run command **adb devices**.
   
  It will show you list of connected devices with your PC.