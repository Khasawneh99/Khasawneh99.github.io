# WAPH-Web Application Programming and Hacking

## Instructor: Dr. Phu Phung

## Student

**Name**: Muhanad Al-Khasawneh

**Email**: alkhasmr@mail.uc.edu

**Short-bio**: Muhanad Al-Khasawneh has keen interests in ethical hacking and secure software development.

![Muhanad's Profile Pic](profilepicresize.jpg)

Lab1 report

Lab overview: In this lab I learned how to use wireshark and implement wireshark to http web servers and how to operate basic web application in C.
https://github.com/Khasawneh99/waph-alkhasmr/tree/main/labs/lab1

Part1 - Task1: The way I used wireshark tool to examine the HTTP protocol was used on how i monitored, analyzed, and troubleshooted HTTP traffic, and with this you can identify potential issues in the network you are looking at.
![This is my HTTP Request](HTTP_Request.png)
![This is my Response messages](Response_messages.png)
![This is my HTTP Stream](HTTP_Stream.png)

Part1 - Taks2: The Telnet tool is connected to a web server at port 80 through the terminal, then you will type the HTTP request and get the HTTP response from the server. 
![This is my telnet request](telnet_request.png)
![This is my telnet response](telnet_response.png)

Part2 - Task1: I wrote a basic hello world program in c and named the file helloworld.c. Then I installed the gcc compiler and then compiled the helloworld.c file. I had to first enable CGI daemon then I had to copy the CGI program to deploy it. Once you complete those steps you can type on the web browser localhost/cgi-bin/helloworld.cgi and then the program will be visiable. 
![My demo Helloworld](demo_hellowrld.png)

Part2 - Task2: 
a) In this task I have successfully developed a simple helloworld.php page that says my name on the site when you look it up on the browser. also I will show you the code I typed to make this work. 
![This is my helloworld.php](helloworld_php.png)

b) The same way on how I made the helloworld.php file is the same way i made the echo.php file. whats cool about this echo file we used a $_REQUEST[] and it retrieved input and can GET and POST and this makes it very convenient for attackers to hack your application.
![This is my echo.php](echo_php.png)

Part2 - Task3: 
a) The way I used the wireshark to examine the HTTP GET request and response for echo.php was I edited it to say my name and what I wanted on the echo server. Then I started the wireshark server and went and edited the echo server and then paused the wireshark to get the end results. The pictures are down below. 
![This is the first wireshark with echo](echo_GET.png)
![This is the second wireshark with echo](echo_HTTP.png)

b) For this part we used HTTP client - curl and this sent a HTTP POST request to the command terminal which allowed us to create the curl and then I used wireshark to change the data input field on the application to my name. 
![This is the corresponding HTTP stream in wireshark](LAB1_PART3.png)

c) The HTTP POST request hides data from the general users and the HTTP GET request is more dangerous and easier for attackers to come hack you because all the parameters are viable in the address bar. 
