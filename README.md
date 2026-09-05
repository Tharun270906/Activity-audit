

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

<img width="1533" height="873" alt="Screenshot 2026-09-04 234327" src="https://github.com/user-attachments/assets/6507f562-e611-4950-b81f-aa16e9255e83" />

## 2.	CloudTrail Event History 

<img width="1533" height="871" alt="Screenshot 2026-09-05 004817" src="https://github.com/user-attachments/assets/3c5ef8b9-2f89-42d6-95d5-d5d8a9dd2700" />


## 3.	CreateBucket Event Details 

<img width="1535" height="871" alt="Screenshot 2026-09-05 004540" src="https://github.com/user-attachments/assets/1f2eb737-edac-4da4-8e88-5bc3698e151f" />


## 4.	Second CloudTrail Event Details 

<img width="1535" height="871" alt="Screenshot 2026-09-05 004540" src="https://github.com/user-attachments/assets/9c07ab74-b299-43d2-91cb-d34296e05fd1" />


## 5.	Final Audit/Observation Table

<img width="1535" height="868" alt="Screenshot 2026-09-05 004615" src="https://github.com/user-attachments/assets/8337fb4d-c9b3-463c-91ae-fa1971652d62" />



### Result

The cloud activities in AWS were successfully audited using AWS CloudTrail Event History. The events were analyzed based on user identity, event name, event time, event source, AWS Region, read-only status, and error status, demonstrating CloudTrail's role in monitoring and accountability. 

