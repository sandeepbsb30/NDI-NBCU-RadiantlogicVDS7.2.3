# NDI-NBCU-RadiantlogicVDS7.2.3
 NDI act as an identity provider for NBC Identity  Management. As per the requirementAs per the requirement from some client  they need data/attribute from Different sources i.e. NDI, Exchange, AD so they  have to hit different server again and again. So, to overcome this we are using  VDS.
1.NBC Universal Directory Infrastructure:
NDI(NBCUniversal Directory Infrastructure) that holds identity information of 
Employee and contractor. NDI act as an identity provider for NBC Identity 
Management.We received feed from different HR (i.e. SAP,Comcast,USJ,etc.) 
into flat file which is pipe separated. We have schedule jobs for different HR at 
our end which calls shell job and which thereafter calls the Perl Script and 
loaded the data into NDI. A Meta Directory system MDS provides for the flow 
of data between one or more Directory services and databases, in order to 
maintain synchronization of that data, and is an important part of Identity 
management systems.The data from source to destination flows through 
channel known as Connector. As per the requirement we have set some rules in 
connector which allow specific data to flow.We are having PingDirectory to 
store data in a Directory. It is able to protect sensitive identity data from 
breach, and flexible enough to store unstructured data and allow all applications 
to easily access user data when they need it.
Apart from this we are using VDS(RadiantLogic FID) as a standard 
edition/Cluster based in our project. 


