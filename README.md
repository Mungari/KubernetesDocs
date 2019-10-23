## KUBEDOCS // OC DOCS

---------------------------------------------------------------------------------------------

## oc new-app mysql MYSQL_USER=user MYSQL_PASSWORD=pass MYSQL_DATABASE=testdb -l db=mysql

creates an application based on an image from DockerHub

## oc new-app --docker-image=myregistry.com/mycompany/myapp --name=myapp

creates application based on a private reg

## oc new-app https://github.com/openshift/ruby-hello-world --name=ruby-hello

creates application based on GIT repo

----------------------------------------------------------------------------------------------


----------------------------------------------------------------------------------------------

Useful commands:

## oc get all 

Shows most important components of a cluster, like NAME, DOCKER REPO, TAGS, UPTIME, RESTARTS, AGE..

## oc describe RESOURCE

gets more information about a resource

## oc export

exports resource definition (in YAML format, can be changed with -o)

## oc create

create resource from definition

## oc edit

edit resource definition

## oc delete RESOURCE_TYPE name

## oc exec POD_NAME [option][command]
 
allows user to exec commands inside a container

## oc rsh POD_NAME [options]

opens interactive shell inside the container

----------------------------------------------------------------------------------------------
