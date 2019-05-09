## Environment variables

#### on macOS

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
  
#### on Linux distributons