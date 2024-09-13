# holbertonschool-system_engineering-devops

## Web Infrastructure Design

### Requirements:

- A README.md file, at the root of the folder of the project, is mandatory
- For each task, once you are done whiteboarding (on a whiteboard, piece of paper or software or your choice), take a picture/screenshot of your diagram
- This project will be manually reviewed:
- As each task is completed, the name of that task will turn green
- Upload a screenshot, showing that you completed the required levels, to any image hosting service (I personally use imgur but feel free to use anything you want).
- For the following tasks, insert the link from of your screenshot into the answer file
- After pushing your answer file to GitHub, insert the GitHub file link into the URL box
- You will also have to whiteboard each task in front of a mentor, staff or student - no computer or notes will be allowed during the whiteboarding session
- Focus on what you are being asked:
- Cover what the requirements mention, we will explore details in a later project
- Keep in mind that you will have 30 minutes to perform the exercise, you will get points for what is asked in requirements
- Similarly in a job interview, you should answer what the interviewer asked for, be careful about being too verbose - always ask the interviewer if going into details is necessary - speaking too much can play against you
- In this project, again, avoid going in details if not asked

### Tasks

0. Simple web stack

On a whiteboard, design a one server web infrastructure that hosts the website that is reachable via www.foobar.com. Start your explanation by having a user wanting to access your website.

Requirements:

1 server
1 web server (Nginx)
1 application server
1 application files (your code base)
1 database (MySQL)
1 domain name foobar.com configured with a www record that points to your server IP 8.8.8.8

1. Distributed web infrastructure

On a whiteboard, design a three server web infrastructure that hosts the website www.foobar.com.

Requirements:

2 servers
1 web server (Nginx)
1 application server
1 load-balancer (HAproxy)
1 set of application files (your code base)
1 database (MySQL)

2. Secured and monitored web infrastructure

On a whiteboard, design a three server web infrastructure that hosts the website www.foobar.com, it must be secured, serve encrypted traffic, and be monitored.

Requirements:

3 firewalls
1 SSL certificate to serve www.foobar.com over HTTPS
3 monitoring clients (data collector for Sumologic or other monitoring services)

3. Scale up

Requirements:

1 server
1 load-balancer (HAproxy) configured as cluster with the other one
Split components (web server, application server, database) with their own server

## Web server vs App server

Web Server vs Application Service

A web server is a software that stores and delivers content to clients who request it, such as text, images, videos, and application data. The most common communication protocol is HTTP, and the content can be static or dynamic. Web servers can cache content to speed up delivery and can limit the speed of response to different clients.

On the other hand, an application service is a set of technologies that interact with the application environment to ensure its performance, security, and operability. These services include traffic management, web application firewalls, load balancing, DDoS protection, and API management. Application services help organizations improve the efficiency, adaptability, and security of their applications.

Differences:

- A web server focuses on delivering content to clients, while an application service focuses on ensuring the security and performance of the application.
- A web server is a software that runs on a server, while an application service is a set of technologies that integrate with the application.
- A web server can cache content, while an application service can manage traffic and protect against attacks.
Conclusion

In summary, a web server is a software that delivers content to clients, while an application service is a set of technologies that ensure the security and performance ofthe application. Both are important for content delivery and application security, but they focus on different aspects.

## Author

Mitzael Pitre De Jesus

mitzaelpitredejesus@gmail.com