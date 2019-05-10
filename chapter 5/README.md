## Troubleshooting guide

#### How to get app package and launch activity ?
    Use below commands to get
    
    Package name
    aapt dump badging /path/to/apk | grep package:\ name
    
    Launchable Activity
    aapt dump badging /path/to/apk  | grep launchable-activity:\ name