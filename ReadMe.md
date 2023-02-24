This is a super simple Base64 encoded PowerShell script wrapped in a batchfile

*it parses the file urls.txt (must be present in same directory), this file should contain a simple list of URLs/URIs to be tested by the script. 

*it generates logfile.txt that contains the following information:

  SiteName: \<url\> ErrorCode: \<HTTP Error code or System error Notification\> TimeStamp: \<Windows Native Timestamp\>



It is used as a simple drop in test script. 
