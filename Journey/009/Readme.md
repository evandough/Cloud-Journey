# AWS Lightsail

## Introduction

I wanted to showcase that I not only understood but could implement instance creation, networking, backups, and migrations. Creating a **WordPress** website would be an exquisite way to demonstrate this and since I created an **AWS** account this can be done using **AWS Lightsail**. 

## Use Case

**AWS Lightsail** provides an option to create an instance based off of a **WordPress** blueprint that runs on **Linux**. When creating the instance you can pick the size and automate snapshots (aka backups). Once your instance is up-and-running, this is where the fun begins. You can view the metrics, snapshots, and create static IPs in the instances various tabs. 

## Cloud Research / Documentation

- [AWS Lightsail features](https://aws.amazon.com/lightsail/features/?opdp2=features/?pg=ln&sec=hs)
- [AWS Lightsail vs EC2](https://aws.amazon.com/free/compute/lightsail-vs-ec2/)

## Implementation

Once you create your **AWS Lightsail** instance, you'll want to do the following:
- In the instance, under the Snapshots tab, you can look at your Snapshots.
  - Depending on your budget you can setup automatic snapshots or manually create snapshots
- In the instance, under the Networking tab, you can attach a Static IP
  - Static IPs help with up-time when swapping IPs and make IP swaps easier to manage - this eliminates having to update DNS records if you restart your instance or have to migrate in the future
- In the instance, under the Metrics tab, you can view your instance's metrics 
- In the instance, under the Connect tab, you can connect to your instance using SSH to get the username and password
- Once you have the username and password you'll login to your **WordPress** site

BOOM! Now it's the fun bit where the only thing left to do is to design your **WordPress** site. 

