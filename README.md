# AUDITING CLOUD ACTIVITY USING AWS CLOUDTRAIL

### Aim

To audit and monitor cloud activity in AWS using AWS CloudTrail by viewing and analyzing recorded AWS events.

### Requirements

* AWS Account
* Web Browser
* Internet Connection
* Amazon S3 access
* AWS CloudTrail

### Procedure

1. Log in to the AWS Management Console and open **AWS CloudTrail**.
2. Select **Event history** to view recent AWS activity.
3. Select an S3-related `CreateBucket` event and open its details.
4. Record the **Event Time, User Name, Event Name, Event Source, AWS Region, Read-only status, and Error Code**.
5. Return to Event history and select another CloudTrail event.
6. Open the event details and record the important audit information.
7. Compare both events based on their time, user, event name, service, region, read-only status, error status, and activity.
8. Identify **who, what, when, where, and result** for each event.
9. Prepare the final audit/observation table using the recorded information.
10. Capture screenshots of the CloudTrail dashboard, Event History, event details, and final audit table.

The experiment procedure and required observations are based on the uploaded Experiment 5 document.  

### Output:
## 1.	AWS CloudTrail Dashboard 

<img width="1918" height="1198" alt="image" src="https://github.com/user-attachments/assets/a419dcd3-ef5b-4282-9033-f9215f770dad" />

## 2.	CloudTrail Event History 

<img width="1918" height="1198" alt="image" src="https://github.com/user-attachments/assets/8f457e27-d93c-499d-ae65-dbf2ee0b05a9" />


## 3.	CreateBucket Event Details 

<img width="1918" height="1197" alt="image" src="https://github.com/user-attachments/assets/2b39b5d1-800f-49f6-b8c4-d5a970d9fb28" />


## 4.	Second CloudTrail Event Details 

<img width="1918" height="1196" alt="image" src="https://github.com/user-attachments/assets/f41d24d4-7c70-4fbb-8d28-affbbd46c755" />


## 5.	Final Audit/Observation Table

<img width="1918" height="1197" alt="image" src="https://github.com/user-attachments/assets/4c43546b-afd4-4d04-89d8-fd1317724518" />



### Result

The cloud activities in AWS were successfully audited using AWS CloudTrail Event History. The events were analyzed based on user identity, event name, event time, event source, AWS Region, read-only status, and error status, demonstrating CloudTrail's role in monitoring and accountability. 
