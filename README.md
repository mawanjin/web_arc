tomcat 下配置 URIEncoding 如下:

<Connector port="8080" protocol="HTTP/1.1"
                         connectionTimeout="20000"
                         redirectPort="8443"
                         URIEncoding='UTF-8' />
