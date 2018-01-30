# micropython-esp8266-websocket-uart
To use UART0 port micropython (esp8266) through connection of websocket
This websocket project is based at upy-websocket-server. The reference is below 


1) Modify the boot.py at line 12 to connect on your wifi
- do_connect(`<ESSID>`, `<PASSWORD>`)
2) Upload all scripts and HTML page to device
3) Restart the device
4) Execute the `import websocket_demo`.
5) If you want to start the application directly,  put "import websocket_demo" in the end of boot.py


### Tutorial
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](https://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)


References:
[https://docs.micropython.org/en/latest/esp8266/index.html]
[https://www.python.org/]
[https://github.com/espressif/esptool/]
[http://micropython.org/download#esp8266]
[https://github.com/adafruit/ampy]
[https://www.putty.org/]
[https://github.com/BetaRavener/upy-websocket-server]
