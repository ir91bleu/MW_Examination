# MW_Examination
Applications to test the behavior of MW.

###################
# SleepSeconds.war#
###################

Usage: You can pause execution for seconds you like.
1. Deploy this war file on the WebApplocation Server you want to test behavior.
2. Execute this application in WebBrowser or Terminal.
   2.1. in WebBrowser
   - input "http://<address>:<port>/SleepSeconds/test?<seconds>" to the address bar.
   2.2. in Terminal
   - type "curl  http://<address>:<port>/SleepSeconds/test?<seconds>"


#################
# ConnectDB.war #
#################

Usage:You test whether the datasource on WebApplication Server can connect DB. 

1. Deploy this war file on the WebApplocation Server you want to test behavior.
2. Execute this application in WebBrowser or Terminal.
   2.1. in WebBrowser
   - input "http://<address>:<port>/ConnectDB/test?<JDBC NAME>" to the address bar.
   2.2. in Terminal
   - type "curl  http://<address>:<port>/ConnectDB/test?<JDBC NAME>"
3. You get succsess message if connection is fine.

 
