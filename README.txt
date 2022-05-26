Project uses: Java, JavaScript, HTML, and CSS files

How to install:
- First download the .zip or .WAR file
- Once download select which file to import

- If .zip file is selected:
	- Click File -> Import -> Expand 'General' tab -> Existing Projects into Workspace
	- Select second row (Select archive file:)
	- Navigate to .zip file contents and select
	- Click Finish to import file

- If .WAR file is selected:
	- Click File -> Import -> Expand 'Web' tab -> WAR file
	- Browse to select .WAR downloaded file
	- Click Finish to import file


How to run:
- Expand the project 
- Then expand the: 'src' folder -> 'webapp' folder
- Right-click on the SisApp.html file
- Select: Run As -> 1 Run On Server
- The application will be presented on the users default browser (Google chrome)
Entries can be entered into the two fields to see if they are valid. If the entries are invalid, and error message 
will be presented.

How to test application:
To test the application, simply copy the curl commands listed below. Next, paste these commands one at a time into
the terminal to recieve the output.

curl -X GET "http://localhost:8080/Ruthirakuhan_SIS-v2/Sis?prefix1=Rodrig&credits=20&reportAjax=true"
curl -X POST "http://localhost:8080/Ruthirakuhan_SIS-v2/Sis?prefix1=Rodrig&credits=20&reportAjax=true"
curl -X GET "http://localhost:8080/Ruthirakuhan_SIS-v2/rest/students?namePrefix=Rodrig&credits=20"
curl -X POST "http://localhost:8080/Ruthirakuhan_SIS-v2/rest/students?sid=cse4413&givenName=Test&surName=Run&creditTaken=90&creditGraduate=120"
curl -X DELETE "http://localhost:8080/Ruthirakuhan_SIS-v2/rest/students?sid=cse4413"

What was the system tested on:
- The user interface, SisApp.html, was tested on a google chrome browser (default).
- The test cases were tested on the command prompt(cmd) using Windows 11.
