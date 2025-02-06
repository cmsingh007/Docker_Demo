FROM ubuntu:24.04
RUN apt-get update
WORKDIR /downloads
ENV app_host='localhost' \
    app_node='example_node' \
    ABC=xyz
COPY . .
ADD https://raw.githubusercontent.com/LondheShubham153/kubernetes-in-one-shot/refs/heads/master/apache/role-binding.yml a1.txt
RUN chmod 777 a1.txt
#RUN useradd -m cloudboss
#USER cloudboss
EXPOSE 5000
ENTRYPOINT [ "sleep" ]
CMD [ "20s" ]