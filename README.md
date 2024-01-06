# To do
* read the RFC
* do some tests with telnet and NGINX before 

# Web server 
* its prinmary funciton: to store, process, deliver web pages to clients
* its secondary function: receiving content from clients (submitting web forms, including the uploading of files)
* the communication between client and server takes place using the HTTP
* a page delivered is an HTML documents
* multiple web servers may be used for a high-traffic website

# The Hypertext Transfer Protocol (HTTP)
* an application protocol
* for distributed, collaborative, hypermedia information systems
* the foundation of data communication for the World Wide Web, where hypertext documents include hyperlinks to other resources 
* was developed to facilitate hypertext and the World Wide Web
* HTML document includes the text content and may include images, style sheets, scripts 
* a user agent (web browser, web crawler) initiates communication by requesting a specific resource using HTTP 
* the server responds with the content or an error message
* the resource is typically a real file on the server’s secondary storage (but not necessarily, depends on how the webserver is implemented)

# NGINX
* a web server
* HTTP-сервер
* SMTP/IMAP/POP3-прокси сервер
* can also be used as a reverse proxy, load balancer, mail proxy, HTTP cache
* простой, быстрый, надёжный, не перегруженный функциями
* целесообразен для статических веб-сайтов
* целесообразен обратный прокси-сервер перед динамическими сайтами

