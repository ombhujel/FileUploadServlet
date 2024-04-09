This is a basic file uploader, and you can directly upload the .war file in Tomcat, however, I implemented Apache HTTPD to listen to all the incoming request and then based on the request, send it back to the destined Tomcat project.

While implementing in a personal computer, all the ports and IP address needs to be configured both in computer and routers, and all the modules should be implemented properly for sending request back and forth, so that the traffic is directed to the particular project.

All the system design can also be uploaded on cloud, that way the IP address and Ports can be fixed easily without worrying about router settings.
