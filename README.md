#This bash script is a quick way to monitor any service in Linux
#If the service is stopped it will try to restart is and send a mail to the user that the service is stopped
#It will attempt to restart the service if the service is stopped
#I use this at work to monitor splunk service, but this can be used for any service monitoring
#configure the smtp server, service name and email ID in the script
#This job has to be run as a cron. See below
#*/3 * * * * /Path/to/file/SplunkServiceMonitor.sh
#Due credits to the creator. I referenced this from an online source
