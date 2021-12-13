Install revel.go using the following command:
go get github.com/revel/revel  

In order to run the scaffold tool, we should install one more supplementary package:
go get github.com/revel/cmd/revel

Create project template
revel new railApi


Out of all those boilerplate directories, three things are important for creating an API. Those are:

app/controllers
conf/app.conf
conf/routes

revel run github.com/git-user/chapter4/railAPIRevel

