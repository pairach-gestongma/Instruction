# Instruction

## Maven
You need to add this line into your settings.xml (or uncomment if it's already there).

<localRepository>C:\Users\me\.m2</localRepository>
Also it's possible to run your commands with mvn clean install -gs C:\Users\me\.m2\settings.xml - this parameter will force maven to use different settings.xml then the default one (which is in $HOME/.m2/settings.xml)

## How to setup JDK without install !!!
You can extract the JDK folder from the Installation EXE.

Check this link for the steps. The post was for JDK 1.7 it will work for JDK 1.8 also

Do the following.

Steps

1. Download JDK from Oracle
2. Download and Install 7-zip from here
3. Open installition exe using 7-Zip
4. Extract the tools.zip
5. Extract the content of tools.zip to a folder (e.g. c:\jdk).
6. Open the extracted folder in cmd prompt.
7. Execute for /r %x in (*.pack) do .\bin\unpack200 -r "%x" "%~dx%~px%~nx.jar" command
8. Set JAVA_HOME to the jdk (e.g c:\jdk) folder.
9. Add %JAVA_HOME%/bin to the PATH env variable.

Testing

Run the following command to check the installation, it will print the version of JDK.

c:> javac -version
javac 1.7.0_51
NOTE: Tested with JDK 1.7 and 1.8

Update

Edited the answer to add the steps in the answer itself instead of the link to a blog post.

cr.https://stackoverflow.com/questions/27012722/get-oracle-java-1-8-in-windows-without-installing-it

## Git
1. git clone https://github.com/pairach-gestongma/Instruction.git or
  git clone https://Pairach.G@gitlab.com/PairachG/ABBYYWeb.git

## Svn
1. svn --version
2. 
