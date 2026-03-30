FROM almalinux:9
RUN dnf install nginx -y 
RUN rm -f /usr/share/nginx/html/index.html
ADD ADD https://raw.githubusercontent.com/rahulkommavarapu/dockerfile/refs/heads/main/RUN/Dockerfile  
CMD ["nginx","-g","daemon-off"]






# FROM almalinux:9

# RUN dnf install nginx -y && dnf clean all

# RUN rm -f /usr/share/nginx/html/index.html

# ADD https://raw.githubusercontent.com/rahulkommavarapu/dockerfile/main/RUN/Dockerfile /usr/share/nginx/html/index.html

# EXPOSE 80

# CMD ["nginx","-g","daemon off;"]