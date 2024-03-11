# multibranch-sample-app

add content

root@53eb846526ea:/# docker run -e JENKINS_OPTS="--httpPort=-1 --httpsPort=8443 --httpsCertificate=/etc/ssl/mi_certificado.crt --httpsPrivateKey=/etc/ssl/mi_dominio.key" jenkins/jenkins:lts
docker: Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?.
See 'docker run --help'.
