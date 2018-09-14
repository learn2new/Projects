# Let's put different types of Ideas 

1. ======== Configuring Monitoring System (Open Source) ========================

Need to create a Grafana based monitoring system which can do the following out of the box:
A time series database as a backend for Grafana which is scalable and can support data of upto 5000 servers.

Custom Collectd (or any other agent) which can be installed on a server which will send metrics to time series database.
An integration with email and pagerduty is required so that alerts can be sent over email as well as to PagerDuty in parallel.

EC2 Metrics (CPU, Disk, Memory, Status Checks, i.e. AWS Metrics)
CPU and Status Checks metrics will be imported from Cloud Watch to Grafana
Memory and Disk metrics would be collected using Agents like CollectD
This would entail a standard installable file to start collection of data with minimum to no complicated action for installation, i.e. execute a simple Script to complete the necessary installation & configuration on the server.
Application Metrics collection using collectd or similar system for following applications along with configuration of the agent so that it can collect the required information by connecting with the desired application and in case the pre-requisites do not exist then this script should be able to complete the desired configuration as well, for e.g. for collecting apache metrics apache sub status module has to be enabled/configured so the script should be able to do that without requiring manual action:

Apache
MySQL
nGinx
Varnish
Tomcat
Redis
MongoDB
Docker
Java Application Metrics


Custom Dashboards for CPU and all the metrics that have been imported to time series database.

A Standard dashboard which captures:

CPU utilization dashboard showing grouping of servers and a email alert for each threshold that needs to set.

Email functionality has to be setup as well in Grafana.

Other Standard Dashboards includes graphs for various Metrics like Disk, Memory, mySQL metrics

Application performance dashboards based on response times recorded using collectd or similar agent.

Custom Dashboards based on Applications like
Java Application Metrics based on java/tomcat metrics
mySQL Slow Query Dashboard, query performance, system health, application health with thresholds.

This is a one time project and work needs to be delivered within a week or 10 days (at max)

Dashboard list that I have given above is not inclusive and I will provide more details as to what else would be needed. It is going to be a 8-10 different thresholds and graphs on metrics for each application/service identified above. 

2. Create an infrastructure and structure for a microservice product on AWS automatically deployed with Teraform.
Create an infrastructure for a microservice product programmed in python, java and go. all infrastructure sould be created on Terraform and should provide a fully automated install and a CI / CD pipilene updates from git repository.


