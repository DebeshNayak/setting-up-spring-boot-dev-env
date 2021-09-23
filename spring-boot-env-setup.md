# Configure Spring Boot Development Environment in Windows 10

## Installing and Running Java 
1. Download latest JDK
   1. Open [jdk.java.net](http://jdk.java.net/)
   2. Choose the **Ready for use** version
   3. Download the **Windows / x64** version 
   4. Unpack the downloaded zip file in **C:\dev\tools** folder (Although not required but I prefer this folder structure)
2. Setup JAVA_HOME enviroment variable
   1. Copy the path of the JDK directory path
   2. Open Windows Setting -> Search for **Edit the system environment variables**
   3. Inside **System Properties**, click the **Environment Varialbe** button.
   4. Inside **System Variable**, create a new variable.
   5. Mention the **Variable name: JAVA_HOME**
   6. Inside **Variable value** mention the JDK directory path
3. Update PATH enviroment variable 
   1. Update the existing PATH variable
   2. Add the value **%JAVA_HOME%\bin**
   3. Click OK and exit the System Property window.
4. Verify correct installation
   1. Open new Command Prompt
   2. Type the command **java --version**

** Installing and Running Maven
1. Download latest Maven
   1. Go to [maven.apache.org](http://maven.apache.org/)
   2. Click on the left hand side **Download** link
   3. Inside [Files](https://maven.apache.org/download.cgi#files) -> Download the **Binary zip archive** 
   4. Unpack the downloaded zip file in **C:\dev\tools** folder (Although not required but I prefer this folder structure)
2. Setup M2 environment variable
   1. Copy the Maven directory path
   2. Edit the system environment variable
   3. Inside **System Variable**, create a new variable.
   4. Mention the **Variable name: MAVEN_HOME**
   5. Inside **Variable value** mention the Maven directory path
3. Update PATH environment variable
   1. Update the existing PATH variable
   2. Add the value **%MAVEN_HOME%\bin**
   3. Click OK and exit the System Property window.
4. Verify correct installation
   1. Open new Command Prompt
   2. Type the command **mvn --version**