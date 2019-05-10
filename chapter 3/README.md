## Last steps before running test

### Locating elements using UIAutomatorViewer
What Is UI Automator Viewer?
UI Automator Viewer is a tool provided by android SDK. UI Automator Viewer will provide you an user interface to scan and analyse UI components of android software application. Using UI Automator Viewer, We can inspect the android app component hierarchy, Inspect properties of android app components and then we can use those element's properties to create xpath of element and use them in automation test scripts.

### Inspecting App's UI Element Using UI Automator Viewer
We will use default and simple calculator app of android phone to learn how to inspect its's UI elements using UI Automator Viewer tool. Follow the steps given bellow.

- Connect your android device with PC (USB debugging mode should be enabled) as described in [here](https://github.com/thenishant/Getting_started_with_Mobile_Automation/blob/master/chapter%202/README.md#TostartUSBDebuggingmode).
- Run command **"adb devices"** in command prompt to verify device is connected properly with PC.
- Run **uiautomatorviewer.bat** file from **E:\SDK\tools** folder. Click [here](https://github.com/thenishant/Getting_started_with_Mobile_Automation/blob/master/chapter%202/README) to know more about SDK folder. 

 - It will open **UI Automator Viewer** tool's UI as bellow.

    ![](https://i.imgur.com/OV63zpQ.png)

 - Open **Calculator application** in your android phone.
 - In UI **Automator Viewer**, Click on **Device Screenshot image button** as shown in below image.
 
    ![](https://i.imgur.com/nQAM4Pg.png)
    
 - After capturing screenshot of android phone screen, It will **show your android phone's calculator's UI** in UI Automator Viewer as below. 
 - On **left side** it will show you **calculator app's screenshot** which is open in android device.
 - **Right side top** part will show **calculator app's UI element's hierarchy view**. It will display node structure to explain **how elements are arranged**.
 - **Right side bottom** part will show property **detail of selected element**.
 
    ![](https://i.imgur.com/DgbuNpO.png)

    
 - In calculator screenshot (which is display in UI Automator Viewer), Select **button 5** to view it's different properties as shown in bellow image.
    
    ![](https://i.imgur.com/8CtODLI.png)
     
 - It is showing different properties of **button 5** in right side node detail section which we can use to locate it using different element locating strategy. 