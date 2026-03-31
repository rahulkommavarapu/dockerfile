FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# this executes if any user uses your image as thier base os 
ONBUILD COPY index.html /usr/share/ngnix/html/index.html
CMD  ["nginx","-g","daemon off;"]