TOUCH CONTROLLER APK PACKAGE

Files:
- index.html
- manifest.json
- icon-192.png
- icon-512.png

IMPORTANT:
Put a compatible Socket.IO browser client named:
    socket.io.min.js
in the SAME folder as index.html before packaging.

The app now:
1. Lets you enter the PC address, e.g. 192.168.1.100:5000.
2. Saves that address on the phone.
3. Reconnects automatically.
4. Uses the bundled local socket.io.min.js instead of /socket.io/socket.io.js.
5. Keeps the landscape controller layout.

The PC running Flask/Socket.IO still needs to be on the same Wi-Fi network
and its server must be reachable from the phone.
