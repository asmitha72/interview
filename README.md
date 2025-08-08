

1. msg = ping 
  while msg:do
  print $msg

2.from ubuntu:22.04
RUN apt httpd
copy <source> <destination>
expose 8080
volume /app
command [sbin/httpd, foreground]

3. docker build -t web1:v1
 docker push target_repo.domain.net:4443:v1.0.0 
    


