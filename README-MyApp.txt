# Vote Rigging Prevention
We have used Retina Scanner for the purpose of voter identification or authentication.As the Retina Scanner of every individual is unique,it helps in maximizing the accuracy.A database is created containing the Retina Scanner of all voters in the constituency.Repetition of votes will be efficiently evaluated in this system. Hence if this system is employed, the elections would be fare and free from rigging.And in the case of blind people,we will use right thumb impression of that individual.
Thanks to this system that conducting elections would be fare and transparent.



### Prerequisites
Advance Java,Java,Python,MySQL,Python API's(pip such as Pillow , ImageHash)

Java: https://www.oracle.com/technetwork/java/javase/downloads/index.html
Advance Java(Tomcat Server): http://tomcat.apache.org/
Python :https://www.python.org/downloads/
MySQL :https://www.mysql.com/downloads/


## Operation Procedure


Step 1:Run the ImageComparision.py file.It will generate text file containing all the duplicate votes given by an individual. (Here we assume that database has already been created in MySQL server.We took entries of citizen's retinas and of thumb prints(for blind) and stored them in database already.)
Step 2:We have placed the govtfp folder inside the MyApp application of the java Tomcat server.Now we compile the java Servlet program by sitting in the src folder of WEB-INF in our MyApp.The compiled file will therefore be automatically saved in classes folder of WEB-INF.
Step 3:Now we start the Tomcat server through administrator permission.All the applications will automatically be deployed.
Step 4: Now we open the web browser and type- localhost:8080/MyApp in URL.It will give index page of the administrator's web application.
Step 5:Now administrator enter his respective name and password(admin & 1234 in our application).After clicking Login he enters his dashboard page where all the fraud people Aadhar numbers will be displayed and therefore the administrator can take the respective legal actions.
```


## gitHub Details
Please read        for details on our code of conduct, and the process for submitting pull requests to us.


## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
