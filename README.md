# Amazon Rekognition Video Workshop -1

# Getting Started

One way to interact with the AWS platform is by using the [AWS Management Console](https://aws.amazon.com/console/). This intuitive, web-based console allows you to administer all of your AWS resources in a single interface.

## Log In

![Event Engine Dashboard Login Screenshot](img/ee-dashboard-login.jpg)

We will be using AWS Event Engine for the labs in order to prevent you from incurring any expense.

To access the AWS Event Engine Team Dashboard, [open this link in a new tab](https://dashboard.eventengine.run/).

Once the Event has begun, find your name below and enter the 12 digit hash (next to your name) in the Team Dashboard.

From within the Team Dashboard, click on "AWS Console" and then "Open AWS Console". This will open the console in a new tab for you to begin your labs.


!!! warning "IMPORTANT"
    Each attendee will have their own, unique AWS account to perform the labs. Make sure you find your name in the list and only use ** your** hash.  If you don't see your name in the table, please let us know.


| Name              | AWS Event Engine Hash |
| ----------------- | ---------------------- |
| Larry | 9a7c-08da42c934-0b |
| Shruthi | 35d7-08aa382744-6d |
| Lindsay | 74a9-0b50b50cf4-38 |
| Phil | 35fc-0be1e162f4-a9 |
| Sean | 19ce-0a131690e4-1d |
| nonane-1 | 3a9d-05dd3eddd4-1e |
| Lakulesh | 9d42-06bb430ee4-7a |
| Jesse | 778c-0efb30d804-a0 |
| Rahul | 1656-0eafb83b24-df |

!!! info
    These accounts will be available for you to use until close of business on **10/23/2021**

## Verify Region

For this class, we will be doing all of our work out of the **us-east-1 (N. Virgina)** region. To verify you're using the correct region, the region dropdown at the top right of the screen should read _N. Virginia_.

![Console us-east-1](img/region-selection.png)

## Browser

We recommend you use the latest version of Chrome or Firefox to complete this workshop.

## Next Steps

Now that you're logged in to the console (and have the appropriate region selected!!), let's jump in. If you're new to AWS, we recommend taking a look at the [AWS Overview](overview.md) as a primer.




## Lab 0: Starting Amazon SageMaker Studio

<!--
<img align="left" src="img/eyecatch_sagemaker.png"></br></br>
-->

### Beginning the Lab

First we are going to start a SageMaker Studio instance. 

1. From your AWS Console, Type sagemaker in the search bar and then select Select Amazon SageMaker.
![Select SageMaker From Console](img/01-select-sm-console.png)
2. Next Select **Amazon SageMaker Studio** from the SageMaker Console
![Select SageMaker Studio](img/02-select-smstudio.png)
3. Select **Quick Start** and then Click the dropdown for **Execution Role**. Here we allow SageMaker to be able to access any S3 buckets we create 
![](img/03-smstudio-quickstart.png)
4. Select **Create a new role**
![](img/04-smstudio-iam-newrole.png)
5. Ensure the permissions look like the picture and click **Create Role**
![](img/05-smstudio-create-iam-role.png)
6. Verify that the Role was creaed successfully and then click **Submit**
![](img/06-smstudio-create-role-success.png)
7. Your SageMaker Studio environment is now being created (takes 10-15 minutes)
![](img/07-smstudio-create-pending.png)
8. Once the SageMaker Studio environment has been created, click on **Open Studio**
![](img/09-sm-open-studio.png)
9. Wait until the SageMaker Studio environment has finished loading (5-10 mins)
![](img/10-smstudio-loading.png)


### Instructions before running the notebook

1. go to sagemaker console, click on studio and execution role

2. add the following policies 

3. add, rekognition full access, iam full access, sns full access, sqs full access 


proceed back to notebook