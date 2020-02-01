# DB-Implementation project part1
### 1. Brief description:
Main intention was to generate data based on Wisconsin benchmark specification. The data is generated using script written in python language. Once the data gets generated, we load that into PostgreSQL database using "COPY" command.

### 2. System working with and why chose it –
PostgreSQL database. <br />
Reason for choosing this Sytem is: We are familiar and have experience working with this system.  ALso it is quite easy to use. 

### 3. Demonstrate that data is loaded into system:
We used postgres copy command to load the data into the system. Loaded all the three relations - TENKTUP1, TENKTUP2, ONEKTUP into the postgres.<br />
Command used : \copy db.ONEKTUP FROM './ONEKTUP.csv' DELIMITER ',' CSV HEADER;<br />
Below is the snapshot for ONEKTUP relation.
![](Images/onektup.PNG)
Likewise did for other two relations.

### 4. Lessons learnt/ problems encountered:
Lessons learnt : How to create clustered and non clustered indexes on an attribute 
