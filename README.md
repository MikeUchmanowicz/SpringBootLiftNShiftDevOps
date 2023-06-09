# 
# SpringBoot Lift N Shift
Michal A Uchmanowicz, Grand Canyon University, 2023

*Java, Springboot, Thymeleaf, Docker, AWS, Google Cloud, Azure, Heroku*

___

All Documentation may not be posted within this repository due to it being part of the Grand Canyon University Curriculum. Documentation and Details are available upon request. 

___


I created a springboot application and hosted it within several clouds: AWS, Google Cloud, Azure, and Heroku. The cloud hosted springboot Application features a home page and a "pseudo-login", allowing for any input which will take the user to an orders page. The user can see all orders which are retrieved from a MySQL database hosted by the same cloud host. The application features a tracer for logging. Within heroku, the logs are drained and output to loggly. An automated build and deployment was implemented within AWS.

<div align="">
<img alt = "Springboot app running in AWS" src="springbootAWS2.png">
</div>  

Springboot app running in AWS


<div align="">
<img alt = "Springboot app running in Google Cloud" src="springbootGoogle.png">
</div>  

Springboot app running in Google Cloud


<div align="">
<img alt = "Springboot app running in Azure" src="springbootAzure2.png">
</div>  

Springboot app running in Azure



<div align="">
<img alt = "Springboot app running in Heroku" src="springbootHeroku.png">
</div>  

Springboot app running in Heroku, i was unable to get mysqlworkbench to connect as i was at maximum database connections.


<div align="">
<img alt = "Log tracing provided by the Tracer class and AOPConfiguration (in app) within the AWS Logs system." src="springbootAWSLogs.png">
</div>  

Log tracing provided by the Tracer class and AOPConfiguration (in app) within the AWS Logs system.


<div align="">
<img alt = "Log tracing provided by the Tracer class and AOPConfiguration (in app) within the Heroku Logs system." src="springbootHerokuLogs.png">
</div>

Log tracing provided by the Tracer class and AOPConfiguration (in app) within the Heroku Logs system.


<div align="">
<img alt = "Logs within a Heroku application are being drained to Loggly. This is a text search." src="springbootLoggly.png">
</div>

Logs within a Heroku application are being drained to Loggly. This is a text search.


https://www.loom.com/share/527f79d313e943208873cb3991907c93

Automated build and deployment via AWS codePipeline to Elastic Beanstalk. 
