1. Just run file 0StartGridHubAndIts1Nodes
2. The QuanDell laptop ip = localhost = 192.168.2.48
3. The port is using = 4444
4. If the port 4444 is busy --> kill port --> netstat -aon | findstr 4444 --> taskkill /PID 19464 /F
5. Launch to check: 
- http://192.168.2.48:4444/grid/console
- http://localhost:4444/grid/console

Download: 
https://chromedriver.chromium.org/downloads                                (download verion 64bit)
https://www.selenium.dev/downloads/                                        (download verion 64bit)
https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/      (download verion 64bit) 
https://github.com/mozilla/geckodriver/releases                            (download verion 64bit)

Ref: https://www.guru99.com/introduction-to-selenium-grid.html
