# recursion-flume-taildir

The source code for this project comes from flume-ng-1.6.0-cdh5.16.2, which I need to do in order to get more compatibility since my Hadoop version is cdh5.16.2

After testing, I found that even the Apache version was successful

The only thing we need to do is take the flume-taildir-source out of the source code and modify it separately, compile and package it, upload it to the server and replace the $FLUME_HOME/lib package with the flume-taildir-source***.jar.

# step
1.The process method modifies the source code

2.Configure method configuration parameter information

3.Package upload server

4.Parameters are set in the flume configuration
