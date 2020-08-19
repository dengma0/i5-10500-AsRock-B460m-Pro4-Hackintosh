# i5-10500-AsRock-B460m-Pro4-Hackintosh
Hackintosh

```
# Info PC
* matherboard: AsRock B460m Pro4
* CPU: intel Core i5-10500
* GPU: AMD Radeon RX 570
* Network card: BCM94360CS2
# works
- Sleep
- Wake
- Audio
- Ethernet
- Bluetooth
- DisplayPort + HDMI simultaneously
- All USB ports

# Result

![RUNOOB 关于本机](./images/aboutMac.png)
![RUNOOB 节能](./images/battery.png)
![RUNOOB 蓝牙](./images/bluetooth.png)
![RUNOOB 显示器](./images/display.png)
![RUNOOB USB](./images/usb.png)
# Note

The file config.plist. Please change MLB, SystemSerialNumber, SystemUUID , ROM into your code

```
<dict>
    <key>AdviseWindows</key>
    <false/>
    <key>MLB</key>
    <string>xxxxxxxxxxxxxxx</string>
    <key>ROM</key>
    <data>xxxxxxxx</data>
    <key>SpoofVendor</key>
    <true/>
    <key>SystemProductName</key>
    <string>iMac19,1</string>
    <key>SystemSerialNumber</key>
    <string>xxxxxxxxxxx</string>
    <key>SystemUUID</key>
    <string>xxxxxxxx-xxxxx-xxxxx-xxxx-xxxxxxxx</string>
</dict>
```
