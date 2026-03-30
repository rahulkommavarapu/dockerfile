FROM almalinux:9
RUN dnf install nginx -y 
RUN rm -f /usr/share/nginx/html/index.html
ADD https://github.com/rahulkommavarapu/dockerfile/blob/main/RUN/Dockerfile  /usr/share/nginx/index.html
CMD ["nginx","-g","daemon-off"]