# Connect a Physical Android Device via TCP/IP

Steps:
1. Make sure my phone and computer are ***on the same WiFi***.
2. Connect my Android phone via USB.
3. Run the <code>adb devices</code> command.
4. Run the <code>adb tcpip <port_number_for_server></code> command.
6. Disconnect the device from USB
6. <code>adb connect 192.168.4.198:5559</code> - <phone_ip>:<port_number_for_server>.
7. <code>adb disconnect</code> - disconnects every physical device connected this way.

✍ The very [1st link at How ADB Works](https://developer.android.com/studio/command-line/adb) has the steps as well.
