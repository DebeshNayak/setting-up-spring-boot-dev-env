# Configure Spring Boot Development Environment in Windows 10

## Installing and Running Java 
1. Download latest JDK
   1. Open [jdk.java.net](http://jdk.java.net/)
   2. Choose the **Ready for use** version
   3. Download the **Windows / x64** version 
   4. Unpack the downloaded zip file in **C:\Program Files** folder
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