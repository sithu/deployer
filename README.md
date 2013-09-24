deployer
========

Application Deployer to integrate with Github webhook


How to run Deployer as a background process
===========================================

nohup python deployer.py mykey ../app/dropwizard-helloworld/stop.sh ../app/dropwizard-helloworld/build.sh ../app/dropwizard-helloworld/run-forever.sh > /tmp/deployer.log 2>&1&
