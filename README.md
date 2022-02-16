## Automate Start and Stop EC2 Instance in AWS 
### 1. Deploy the Stack 
    a. define the tag started_by=instance-scheduler
    b. define the tag stopped_by=instance-scheduler
### 2. Configure the DynamoDB table 
    a. config: regions -> change based on the region of EC2
    B. period: office-hours -> change by the time of office-hours
### 3. Create the EC2 Instance 
    a. tag -> Schedule: uk-office-hours (based on the tabel in dynamoDB)

Source: https://aws.amazon.com/id/solutions/implementations/instance-scheduler/ 
