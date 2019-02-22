
# Points Distribution Table

For each one of the tasks completed your team will get points. These Points will
be added at the end of the Challenge. The team that has the most points will win
 the challenge:

- [Challenge Competition](#challenge-competition)
- [Points per Tier](#points-per-tier)
- [DevOps Points](#devops)

## Challenge Competition

|####|Name|Tier|Description|Points|
|----|----|----|-----------|------|
|CC-1|Level Up!|CC|Build and deploy a solution that can compete against other teams in an Official Game| 30|
|CC-2|Challenge Champion|CC| Winning the official competition| 20|

## Points Per Tier

### Tier 1 Sensors Array:

|####|Name|Tier|Description|Points|
|----|----|----|-----------|------|
|T1-1 |Sensor Software Running in Raspberry|Tier 1|Get the SensorSuite program running with native deployment on the Raspberry Pi (This task can be skipped and participants can jump directly to T1-2. Teams can only get 5 or 15 points, depending on the method of deployment, Native vs Dockerized)|5|
|T1-2 |My Sensor Containers|Tier 1| Build a container for each sensor in the SensorSuite. Use these containers for the rest of the challenge (Max points a team can get from T1-1 & T1-2 is 15 points)|15|
|T1-3 |Bridge The Gap|Tier 1|Run *Flare* on your machine, and configure your other sensors to reach it|5|

### Tier 2 The Aggregator:

|####|Name|Tier|Description|Points|
|----|----|----|-----------|------|
|T2-1|Start the Aggregator|Tier 2| Run the Aggregator on your machine, show it received data from your SensorSuite|5|
|T2-2|Data smarts| Tier 2| Modify the Aggregator to send all the RAW sensor to a storage repository|5|
|T2-3|My Gateway Container|Tier 2| Build a container for the Aggregator. Use this container for the rest of the challenge|5|

### Tier 3 Data Repository:

|####|Name|Tier|Description|Points|
|----|----|----|-----------|------|
|T3-1 |Data Hog 1|Tier 3|Store all Sensor Data from system|5|
|T3-2 |Data Hog 2|Tier 3|Store all Logs from system|5|
|T3-3 |My Data Repository Container|Tier 3|Build a container with the Data Repository tier. The container should mount external storage volume for persistence.|5|

### Tier 4 Data Analysis Tier

|####|Name|Tier|Description|Points|
|----|----|----|-----------|------|
|T4-1|Analytic Brain|Tier 4| Setup a node or a cluster of Hadoop/Spark/F#(or any language/tool of your choice) to analyze data. This service should get sensor data, analyze them and respond back with "Shield Recommendations" (turning it on or off).|15|
|T4-2 |Microservices Guru|Tier 4|Implement the data analysis as an independent standalone service on its own.|5|
|T4-3|My Analytic Container|Tier 4| Build a container with the Data Analysis tier. Use this container for the rest of the challenge|5|

### Tier 5 Team Client and Control Tier

|#####|Name|Tier|Description|Points|
|----|----|----|-----------|------|
|T5-1|Command and Control|Tier 5| Implement a service that can join the game, retrieve data from the Gateway/Game Controller, Forward this data to the Data Analytics Service and send back the shield recommendations(coming from the analytics service) to the Game Controller. Client & Control should also forward the sensor data to Data Repository Tier or it can write it directly there. |5|
|T5-2 |Microservices Guru|Tier 5|Implement the team client and control as an independent standalone service on its own.|5|
|T5-3|My C&C Container|Tier 5| Build a container with the C&C tier. Use this container for the rest of the challenge|5|

### Tier 6 Data Backup

|#####|Name|Tier|Description|Points|
|----|----|----|-----------|------|
|T6-1|For the Ages|Tier 6|Build a Backup service that takes data and performs backups and stores them in a separate backup data repository. |5|
|T6-2 |Microservices Guru|Tier 6|Implement the data backup as an independent standalone service on its own.|5|
|T6-3|My Backup Service Container |Tier 6| Build a container with the Data Backup service tier. Use this container for the rest of the challenge|5|


## DevOps

|#####|Name|Tier|Description|Points|
|----|----|----|-----------|------|
|DO-1|Docker Me up!|DO| Deployment of the implemented system using Docker-Compose or Docker Swarm| 15|
|DO-2|Service Discovery|DO| Implement Service Discovery between all the containers deployed in the solution| 5|
|DO-3|Service Monitoring|DO| Implement Service Monitoring of all containers deployed in the solution| 5|

<!-- ## Bonus Points

|####|Name|Tier|Description|Points|
|----|----|----|-----------|------|
|BC-1|DevOps Power|BC| Deploy a CD/CI tool-chain, DevOps style, that includes Tiers 1-5 so your team can develop the algorithm to survive the event|20|
|BC-2|Limited Resources|BC| The team commits to only drink water for the entire challenge. It is Mars after all!|10|
|BC-3|The FOSS|BC| The team commits to share all the information about what you are doing. Free and open-source software works even in Space!|10|
|BC-4|Evil Genius|BC| The team commits to not sharing any information with anybody. You and your team are Evil Geniuses!|10| -->
