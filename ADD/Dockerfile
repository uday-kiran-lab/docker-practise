FROM almalinux:9
RUN dnf install nginx-y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/uday-kiran-lab/docker-practise/blob/main/COPY/index.html /usr/share/nginx/html/index.html
RUN chmod +x /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp
CMD ["nginx", "-g", "daemon off;"]