# A demo showcasing MongoDB (Atlas), Stitch and the new MongoDB Change Stream available in 3.6

* More information on Atlas here: https://www.mongodb.com/cloud/atlas
* More information on Stitch: https://www.mongodb.com/cloud/stitch
* More information on Change Stream here: https://docs.mongodb.com/manual/changeStreams/



![Demo](/docs/MongoDBStitchTwitterDemo.PNG "Demo")


So what are we trying to demo here?


**NOTE:** Maven is required to run the application, please do install it if it is not already the case: https://maven.apache.org/install.html 


## Deploy EmpBook

First, you need a running mongoDB instance.

```
git clone https://github.com/schabiyo/EmpBook.git
cd 

```

Then change the configuration file to point to your running mongoDB instance.
If you are pointing to a local MongoGB, the configuration should look like this:

Then start the application by running the following command:

 ```
 mvn spring-boot:run

 ```

Start the SocialRewarder application
----------------

 ```
 git clone
 cd
 mvn spring-boot:run
 
 ```


Start the twitter stream
----------------



```
cd 
mvn spring-boot:run

```


TODO
----------------

* Any suggestion?



If you found this guide lacking please submit an issue or PR through github. We appreciate your feedback.
