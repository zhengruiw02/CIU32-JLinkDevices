# Reference

[1] https://wiki.segger.com/J-Link_Device_Support_Kit

[2] https://www.hed.com.cn/mcuxp

# Adding path
| OS | Location |
| ----- | ----- |
| Windows | C:\Users\\\<USER>\AppData\Roaming\SEGGER\JLinkDevices |
| Linux | $HOME/.config/SEGGER/JLinkDevices |
| macOS | $HOME/Library/Application Support/SEGGER/JLinkDevices |

# Example JLinkDevices folder sturcture
```
\---JLinkDevices
    +---Vendor1
    |   +---DevFamily1
    |   |       Devices.xml
    |   |
    |   +---DevFamily2
    |   |       Devices.xml
    |   |
    |   \---DevFamily3
    |           Devices.xml
    |
    +---Vendor2
    |   +---DevFamily1
    |   |       Devices.xml
    |   |
    |   +---DevFamily2
    |   |       Devices.xml
    |   |
    |   \---DevFamily3
    |           Devices.xml
    |
    \---Vendor3
        +---DevFamily1
        |       Devices.xml
        |
        +---DevFamily2
        |       Devices.xml
        |
        \---DevFamily3
                Devices.xml
```