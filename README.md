# docker-rocket.chat-and-apache

This is Rocket.Chat project setting files by Docker and Apache 2.4.  
Apache use reverse proxy and SSL.  

Internet -> httpd(:80) -> httpd(:443) -> ReverseProxy by Apache -> Rocket.Chat On Docker(:3000)
