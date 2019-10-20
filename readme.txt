continuous integration using jenkins , github and nexus :

- Publish Maven Artifacts to Nexus OSS Using  Maven Jobs


1/ clone the project :
	git clone https://github.com/GSalah/CI_maven.git
 
2/ install nexus (localhost:8081)
	create nexus maven2 (hosted) repository named "nexus-snapshot"
	
3/ install jenkins (localhost:8080)
	create job to deploy the maven project ...
4/ don't forget to change your setting.xml file
	nano (or vim) ~/.m2/setting.xml

Enjoy ;) 
