# Nagios with postfix configured (gmail)


# Buildstep

# Gmail config 

change value of file in conf/sasl_passwd

# Docker build

  - docker build -t myimage/nagios .

# command to run the docker image

docker-compose up -d
