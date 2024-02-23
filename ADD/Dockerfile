FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html     
ADD https://github.com/daws-76s/notes/blob/master/session-01.txt /usr/share/nginx/html/index.html 
CMD ["nginx","-g","daemon off;"]
 