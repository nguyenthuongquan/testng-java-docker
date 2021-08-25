# Running testNG with Selenium Grid on Docker (compose)

1. Run project with Selenium Grid locally
- review files in documents/selenium-grid-web
- Cd to documents/selenium-grid-web run: start 0.StartGridHubAndIts2Node.bat
- Launch http://localhost:4444/grid/console -> Check hub and node ok
- Run the TestNG.xml files --> (5 firefox, 5 chromes launches at once)

2. Run project with Selenium Grid in Docker
- review file 'docker-compose.yml' in documents/docker
- Cd to documents/docker run: docker-compose up
- Launch http://localhost:4444/grid/console -> Check hub and node ok
- Open VNC Viewer, start 2 viewers
- Run the TestNG.xml files --> (5 firefox, 5 chromes launches at once in 2 viewers)