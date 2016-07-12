
## INSTRUCTIONS TO GET ADMIN RIGHTS: ##

1. Go to the link https://onecognizant.cognizant.com/
2. On the app store select “admin rights”
3. Click on the One NSS app and register to get your admin rights.
4. If you have any problems or doubts regarding this click on “expertchat” on your task bar. 
5. The admin rights is required to install MAVEN and JAVA, without admin rights the system variables cannot be edited.
![alt text](https://github.com/CTSJavaTraining/Images/blob/master/expert_touch.png)
	
## MAVEN INSTALLATION STEPS: ##

1.Download Maven from website https://maven.apache.org/download.cgi 
2.Click on the link apache-maven-3.3.9-bin.zip to get the zip file downloaded.
3.Unzip the file and keep it in D:\ drive.
![alt text](https://github.com/CTSJavaTraining/Images/blob/master/maven_download.png)

## MAVEN INSTALLATION: ##

1.Check if JAVA8 is installed in your system
![alt text](https://github.com/CTSJavaTraining/Images/blob/master/Java_Version_Check.png "JAVA_VERSION_CHECK")
	If JAVA 8 in not installed do the following steps.
	a.Raise phoenix request for JAVA 8 software.
	b.Once the software is installed in path “C:\Program Files\Java”
	c.Start-> ControlPanel > System > Advanced system settings
	d.Click on the “edit” button under system variables and add “JAVA_HOME to C:\Program Files\Java\jdk1.8.0_91
	e.Ensure JDK is installed and not JRE
	f.Check if JAVA is installed properly using the command “java -version” in command prompt.
2.Start-> ControlPanel > System > Advanced system settings
3.Click on the “edit” button under system variables and add “M2_HOME= D:\apache-maven-3.3.9-bin\apache-maven-3.3.9” and “MAVEN_HOME= D:\apache-maven-3.3.9-bin\apache-maven-3.3.9”.
4.Also append the following to the path variable under system variable 
	a.%MVN_HOME%\bin; %JAVA_HOME%\bin\
5.In command prompt type the command “mvn --version” to check if MAVEN is properly installed in your system.

## EDITING SETTINGS.XML FILE: ##

1.Go to path “D:\apache-maven-3.3.9-bin\apache-maven-3.3.9\conf”
2.Open settings.xml file and edit the <proxies> tag as:

```xml
<proxies>
    	<proxy>
	      	<id>optional</id>
	     	<active>true</active>
	      	<protocol>http</protocol>
	      	<username>cts\Your EmpID</username>
	      	<password>Provide your password</password>
	      	<host>proxy.cognizant.com</host>
	      	<port>6050</port>
 	</proxy>
</proxies>
```


## DOWNLOAD AND INSTALL GIT: ##

1.Download GIT by clicking on the link https://git-for-windows.github.io/
2.Double click on the file downloaded and select “Run”.
3.Complete the install wizard.
4.Check if GIT is properly installed in your system using command “git --version” in command prompt.

## DOWNLOAD AND INSTALL ECLIPSE IDE: ##

1.Raise a phoenix request for eclipse software “Eclipse Mars”.
2.To raise phoenix request follow the steps given below:
	a.Click on the link https://onecognizant.cognizant.com/.
	b.In the app store search for phoenix.
	c.Give install Eclipse Mars as problem statement.
	d.Raise a request.
	e.If you have further doubts do chat with “experttouch”.
3.Once the software is installed open the folder and double click on the .exe file to open and work with eclipse.
4.Install Maven plugin from store by following the steps given below:
	a.Go to Help -> Eclipse Marketplace
	b.Search by Maven
	c.Click "Install" button at "Maven Integration for Eclipse" section
	d.Follow the instruction step by step till finish.

## OTHER SOFTWARE REQUIRED: ##

1.Please do check if the following software is also available in your system SOAPUI,REST Postman,7ZIP, Jmeter
2.Raise a phoenix request to get these software too.

