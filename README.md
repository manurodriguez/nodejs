# nodejs
Nodejs tests

oc login
oc whoami

oc new-project testing --display-name="Hello World NodeJS"
oc project testing

oc new-app openshift/nodejs-010-centos7~https://github.com/manurodriguez/nodejs.git
oc describe build
oc get svc
oc describe svc/nodejs
oc get pods
oc expose service nodejs
oc get routes
