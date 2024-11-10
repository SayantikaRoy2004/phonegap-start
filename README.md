Microsoft Windows [Version 10.0.22631.4317]
(c) Microsoft Corporation. All rights reserved.

C:\Users\sayantika>java -version
java version "1.8.0_401"
Java(TM) SE Runtime Environment (build 1.8.0_401-b10)
Java HotSpot(TM) 64-Bit Server VM (build 25.401-b10, mixed mode)

C:\Users\sayantika>where java
C:\Program Files (x86)\Common Files\Oracle\Java\javapath\java.exe
C:\Program Files\Java\openlogic-openjdk-11.0.25+9-windows-x64\bin\java.exe

C:\Users\sayantika>"C:\Program Files (x86)\Common Files\Oracle\Java\javapath\java.exe" -version
java version "1.8.0_401"
Java(TM) SE Runtime Environment (build 1.8.0_401-b10)
Java HotSpot(TM) 64-Bit Server VM (build 25.401-b10, mixed mode)

C:\Users\sayantika>"C:\Program Files\Java\openlogic-openjdk-11.0.25+9-windows-x64\bin\java.exe" -version
openjdk version "11.0.25" 2024-10-15
OpenJDK Runtime Environment OpenLogic-OpenJDK (build 11.0.25+9-adhoc..jdk11u)
OpenJDK 64-Bit Server VM OpenLogic-OpenJDK (build 11.0.25+9-adhoc..jdk11u, mixed mode)

C:\Users\sayantika>java -v
Unrecognized option: -v
Error: Could not create the Java Virtual Machine.
Error: A fatal exception has occurred. Program will exit.

C:\Users\sayantika>java -version
java version "1.8.0_401"
Java(TM) SE Runtime Environment (build 1.8.0_401-b10)
Java HotSpot(TM) 64-Bit Server VM (build 25.401-b10, mixed mode)

C:\Users\sayantika>set JAVA_HOME=C:\Program Files\Java\openlogic-openjdk-11.0.25+9-windows-x64

C:\Users\sayantika>set PATH=%JAVA_HOME%\bin;%PATH%

C:\Users\sayantika>java -version
openjdk version "11.0.25" 2024-10-15
OpenJDK Runtime Environment OpenLogic-OpenJDK (build 11.0.25+9-adhoc..jdk11u)
OpenJDK 64-Bit Server VM OpenLogic-OpenJDK (build 11.0.25+9-adhoc..jdk11u, mixed mode)

C:\Users\sayantika>setx SONARQUBE_HOME "C:\Program Files\SonarQube\sonarqube-10.7.0.96327\bin" /M
ERROR: Access to the registry path is denied.

C:\Users\sayantika>setx SONAR_SCANNER_HOME "C:\Program Files\SonarScanner\sonar-scanner-6.2.1.4610-windows-x64\bin" /M
ERROR: Access to the registry path is denied.

C:\Users\sayantika>set SONARQUBE_HOME=C:\Program Files\SonarQube\sonarqube-10.7.0.96327\bin

C:\Users\sayantika>set SONAR_SCANNER_HOME=C:\Program Files\SonarScanner\sonar-scanner-6.2.1.4610-windows-x64\bin

C:\Users\sayantika>set PATH=%PATH%;C:\Program Files\SonarQube\sonarqube-10.7.0.96327\bin;C:\Program Files\SonarScanner\sonar-scanner-6.2.1.4610-windows-x64\bin

C:\Users\sayantika>echo %SONARQUBE_HOME%
C:\Program Files\SonarQube\sonarqube-10.7.0.96327\bin

C:\Users\sayantika>echo %SONAR_SCANNER_HOME%
C:\Program Files\SonarScanner\sonar-scanner-6.2.1.4610-windows-x64\bin

C:\Users\sayantika>sonar-scanner --version
10:59:46.453 INFO  Scanner configuration file: C:\Program Files\SonarScanner\sonar-scanner-6.2.1.4610-windows-x64\bin\..\conf\sonar-scanner.properties
10:59:46.458 INFO  Project root configuration file: NONE
10:59:46.473 INFO  SonarScanner CLI 6.2.1.4610
10:59:46.474 INFO  Java 17.0.12 Eclipse Adoptium (64-bit)
10:59:46.475 INFO  Windows 11 10.0 amd64

C:\Users\sayantika>^A
