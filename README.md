#PayTM Weblog Challenge

#Tools Used: 

AWS EMR Cluster
AWS S3
Zeppelin
Spark SQL
Scala

#Implementation
The solution was done via Zeppelin Notebooks utilizing Spark interpreter in AWS EMR cluster. Although I am more proficient with Python, I wanted to code this challenge in scala to prove that I can create deployable scala programs with some real time experience. Also, using EMR cluster for the first time was a challenge that I enjoyed.

#Inputs
The solution assumes that the log file is stored in S3 bucket “sessionize-weblogs”

#Outputs
The solution publishes to S3 bucket “sessionize-weblogs”, using coalesce to get 1 part file. The output files and the code(note.json) from zeppelin has been uploaded to the Github repository : 

#Sessionization
The sessionization is performed via the default proposed 15 minute window.

