Minimum Requirement for Running the application
------------------------------------------------
Java 8 is installed and JAVA_HOME is set in environment variables
Maven installed.
POSTMAN - for sending RESTFUL Web services 


Instructions to run the Hoover Application
--------------------------------------------
This Application can be run either directly from command prompt or using the .bat file 

1. Run the application directly from command prompt: 
	- In the command prompt browse to the directory where the 'hoover-app-demo' project is extracted
	- Enter the below command to run the application. 
		java -jar jar/hoover-demo-0.0.1.jar
	-Then use the POSTMAN app to send the JSON request using the below url
		http://localhost:8080/hoover
	
	
2. Running from .bat file using command prompt (either hoover_linux.sh or hoover_win.bat)
	- In the command prompt browse to the directory where the "hoover-app-demo" project is extracted
	- execute the .bat or .sh as below 
		C:\project\hoover-app-demo>hoover_win.bat
	-Then use the POSTMAN app to send the JSON request using the below url
		http://localhost:8080/hoover
