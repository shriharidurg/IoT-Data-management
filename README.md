# IoT-Data-management             
Steps to run nifi project.

1.Download apache nifi from https://nifi.apache.org/download.html                                                    
2.Download the final_demo1.xml from nifi_xml folder.                                    
3.Open nifi on localhost.                                                                          
4.Right click,there you will find "upload template" then search for the xml and upload.                   
5.Here we will see a Processor named "demo1" double-click to get inside the Processor.              
6.Again there are some set of Processor.Each Processoris assigned with diffrent task.            
7.csv-json converter,Converts csv file to json file(array based).
8.upload to mongodb ,Which uploads the data to the mongodb.First we need to create a database.And in "putmongodb" Processor add the  
database name.                                                                
9.Here we can add policy in "putmonogodb" Processor itself.                            
10.To retrive it back we a "getmongodb" Processor.                                 
11.The last Processor is for Retention.

