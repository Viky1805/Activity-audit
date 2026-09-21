## Exp_05: Cloud Audit

## Name: Vignesh S

## Reg No: 212224110061

## AUDITING CLOUD ACTIVITY USING AWS CLOUDTRAIL

## Objective 

To audit and monitor cloud activity in AWS using AWS CloudTrail by viewing and analyzing recorded AWS events and identifying important audit information such as user identity, event name, event time, AWS service, region, and operation status.

## Requirements

AWS Account

Web Browser

Internet Connection

Amazon S3 access

AWS CloudTrail

## PART A — ACCESS AWS CLOUDTRAIL

Step 1: Login to AWS

1. Open the AWS Management Console.

2. Sign in using your AWS account.

3. In the AWS search bar, type CloudTrail.

4. Select AWS CloudTrail.

<img width="1917" height="1093" alt="image" src="https://github.com/user-attachments/assets/583b497c-4845-4dc9-8ebb-2a9fc16896c2" />

## Step 2: Open Event History

1. In the CloudTrail navigation menu, select Event history.

2. CloudTrail displays recent AWS activity.

3. Review the available events.

The Event History page may display information such as:

Event time

Username

Event name

Event source

Resource type

Resource name

<img width="1917" height="1097" alt="image" src="https://github.com/user-attachments/assets/cddc3ea1-5fc6-446a-8a40-6017b1e2e467" />


## PART B — ANALYZE A CLOUDTRAIL EVENT

## Step 3: Select an Event

From the Event History list, select an S3-related event.

Click the event to open its details.

Examine the event information and the event record/JSON.

For this experiment, a CreateBucket event can be used.

## Step 4: Analyze the CreateBucket Event

The CreateBucket event indicates that an Amazon S3 bucket creation operation occurred.

Record the following information:

<img width="1917" height="1097" alt="image" src="https://github.com/user-attachments/assets/b375327d-8e68-4887-b4a4-43a40cb523c3" />


## PART C — IDENTIFY ANOTHER CLOUDTRAIL EVENT

## Step 5: Select Another Event

Return to CloudTrail → Event history.

Select another event.

Open its details.

Record the important fields.

For example, an event such as:

AutomatedDefaultVpcCreation

may be present.

This event is associated with Amazon EC2.

<img width="1917" height="1083" alt="image" src="https://github.com/user-attachments/assets/b15706af-5dfe-4796-bc37-17cd5eeff285" />



## PART D — COMPARE THE EVENTS

## Step 7: Prepare the Audit Comparison

Compare the two CloudTrail events.

<img width="1005" height="818" alt="image" src="https://github.com/user-attachments/assets/d4524caa-1633-4abb-adfa-0c5c41edfb37" />

## PART E — SECURITY AUDIT ANALYSIS

## Step 8: Identify Who, What, When and Where

For each event, identify:

## WHO?

Who or which identity performed/generated the activity?

## WHAT?

What AWS operation was performed?

## WHEN?

At what date and time did the activity occur?

## WHERE?

In which AWS Region did the activity occur?

## RESULT?

Was the operation successful or did it generate an error?

## Step 9: Prepare the Final Audit Table

Students should prepare a final table similar to the following:

<img width="1220" height="268" alt="image" src="https://github.com/user-attachments/assets/ff68c0b6-1aa2-4906-bb5f-c171db9b9336" />

## PART F — SCREENSHOTS TO SUBMIT

Students should capture the following screenshots:

1. AWS CloudTrail Dashboard

2. CloudTrail Event History

3. CreateBucket Event Details

4. Second CloudTrail Event Details

5. Final Audit/Observation Table

## RESULT

The cloud activities in AWS were successfully audited using AWS CloudTrail Event History. Different AWS events were examined based on event time, user identity, event name, event source, AWS Region, read-only status, and error status. The experiment demonstrated how AWS CloudTrail provides an audit trail for monitoring, accountability, and investigation of cloud activities.


