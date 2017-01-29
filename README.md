# EasySqlLiteJava
A Class providing high level and easy usage of SqlLite Database engine in Java for beginners

It is Thread Safe and can have multiple read and write clients on differant Threads, The writes areq queved and are written in order of the calls. The one caveat that must be worked out is that you cant initiate a new connection in a thread that has a previous open connection, the precious connection in the same thread must be closed before. 
