Tested on Xiaomi mi A2 google chrome and duckduckgo browsers

Test the project yourself at https://eimantasmockevicius.github.io/mediaLab4/


# Requirements for WebRTC application
There are three options to choose from. 

Option A:
  - Use WebRTC filter application code (https://github.com/webrtc/samples/tree/gh-pages/src/content/getusermedia/filter) and additional filter like Canny Edge filter or any other non existing in the sample.
  - It is also needed to add a slider to control a threshold/gain for your filter. It should work realtime.  

Option B:
  - Use WebRTC filter application code (https://github.com/webrtc/samples/tree/gh-pages/src/content/getusermedia/filter) and add face detector. Tracking.js is good place to start (https://trackingjs.com/examples/face_camera.html).

Option C:
  - It is your chance to show your skills and creativity.
  - You can add extra features to existing WebRTC examples.
  - Or anything other.
  
The general requirements for option A, B & C:
  - Test application on at least two browsers and specify in README.md which version and browser it was.
  - To pass this lab, you have to fully complete an option.  
  
# Important notes
  - SSL server is needed to run this lab material.
  - You will be needed to generate self signed sertificate and set up your web server. 
You can try to use these file servers:  
  - Apache: https://www.raspberrypi.org/documentation/remote-access/web-server/apache.md 
  - Tomcat: http://androidsrc.net/installing-tomcat8-raspberry-pi-3/ 
  - HFS: http://www.rejetto.com/hfs/ or any other server.
Proxy http to https:
  - https://technique.arscenic.org/lamp-linux-apache-mysql-php/apache-le-serveur-http/modules-complementaires/article/installer-et-configurer-le-module-ssl-pour-apache2?fbclid=IwAR1_nXNQlrMIdJ5tilVUyr45xeiA91yw21vhnMxWHnuvY01VTd2FVR_T2ao  
