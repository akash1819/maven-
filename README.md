MAVEN:
its a build tool.
main file is POM.XML (project object model & Extensible markup language)
POM.XML will have entire information of project.
it is used to create artifact (war, jar, ear)
It is mostly used for java-based projects.
It was initially released on 13 July 2004.
Maven is written in java (1.8.0)

RAW: .java (we cant use it)
.java -- > compile -- > .class -- > .jar -- > package -- > .war

.class   : which can be executable
.jar   : group of .class files (works for backend)
.war   : it has frontend and backend code (FE: HTML, CSS, JS & BE: JAVA)
libs   : its a pre defined packages used for code.

ARTIFACTS: its the final product.
JAR = JAVA ARCHIVE
WAR = WEB ARCHIVE
EAR = ENTERPRISE ARCHIVE
PLUGIN: its a small software which automates our work.
with the plugins we can use tools without installing them.

GOAL: its a command used to perform task.
MAVEN follows a lifecycle

mvn compile   : to compile the source code
mvn test   : to test the code
mvn package   : to create artifact (project directory)
mvn install   : to create artifact (maven home dir .m2)
mvn clean packge: to perform entire goals
mvn clean   : to delete target
🎯 SETUP:
Create aws ec2
yum install java-1.8.0-openjdk maven git -y
git --version
mvn --version

git clone https://lnkd.in/gtDZWYGD
cd jenkins-java-project.git
