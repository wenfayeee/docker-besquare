FROM httpd:2.4.33-alpine
COPY demo.apache.conf /usr/local/apache2/conf/demo.apache.conf
RUN echo "Include /usr/local/apache2/conf/demo.apache.conf" \ 
    >> /usr/local/apache2/conf/httpd.conf