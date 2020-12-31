# Cognived Product

Steps to Run the App
1) Clone Repo
2) Make sure node is installed in machine
3) Run "npm install" in terminal where you cloned the repo which would install all the required dependencies from package.json
4) Run the sever.js file -> node server.js
5) Once 4th step is done.....open google chrome tab and hit "localhost:3000"

Note: WebRtc Api does not allow the access to webcam and microphone if domain is not from secure origin (i.e https) and by default localhost is considered as secured

Currently the App is running on "http://cognived.synology.me:3000" as well but it won't be able to access your webcam and microphone as I mentioned above, so workaround for this until we get SSL certificate for same is set flag in google chrome ->hit "chrome://flags/#unsafely-treat-insecure-origin-as-secure" in google chrome tab where you need to add "http://cognived.synology.me:3000" url in comment box and make it enabled
