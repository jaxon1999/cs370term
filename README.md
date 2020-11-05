# cs370term
CS370 Term Project

Description:
Virtualization is a tool that is used across the world. While it has many benefits, it also has its downfalls. For example, vitualization is slow and comes at a high cost. This is because in virtualization, the host machine uses different instances of a kernel process and guest operating systems. The time it takes to launch multiple guest operating systems is much higher than using containers, which drives up server costs. Docker containers impove efficiency and lower the total cost of the individual or company that is using said Docker containers. It dramatically improves the efficiency of virtualization because the applications, also known as images or containers, run off of the same kernel and use namesping and control groups to devide up what part of the host machine each image can use and how much memory taht image can take up. Containerization deminishes the start up time requierd which allows more containers to run. This causes efficiency to rise and server costs to go down. 

Usage:
To run the RESTful server the following command launches the server:
$ java -cp target/TermProject-1.0-SNAPSHOT-jar-with-dependencies.jar RestfulServer

Docker:
