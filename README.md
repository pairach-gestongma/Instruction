# Instruction

Maven
You need to add this line into your settings.xml (or uncomment if it's already there).

<localRepository>C:\Users\me\.m2</localRepository>
Also it's possible to run your commands with mvn clean install -gs C:\Users\me\.m2\settings.xml - this parameter will force maven to use different settings.xml then the default one (which is in $HOME/.m2/settings.xml)
