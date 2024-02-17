FROM almalinux:8
RUN yum install nginx -y
ENV TRAINING="DEVOPS" \ 
    TRAINER="Sivakumar" \
    DURATION="120HRS"
CMD ["nginx","-g","daemon off;"]

# TRAINING, TRAINER, DURATION are keys
# DEVOPS, Sivakumer, 120HRS are values
# so you can use these variables in docker container