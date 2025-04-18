# Creating An AWS Budget & Alerts

## Introduction

If you recall my day 1 first post talking about [setting up a budget within my Azure account](https://github.com/evandough/Cloud-Journey/blob/main/Journey/001/Readme.md), you know I'm not trying to break the bank. I wanted to get hands-on experience with **AWS** and created an account. Before I started provisioning resources I wanted to ensure that my bill wouldn't be colossal, which is why a budget was created with alerts to notify me if spending is getting out of hand. Some would call this part of the **FinOps** ecosystem...and I like the sound of a buzz word.  

## Prerequisite

You're going to need an **AWS** account to set this bad boi up. 

## Resources Used

- [This is AWS documentation on how to create your budget](https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-create.html)
- [If you prefer a walkthrough guide, this is AWS YouTube video on how to setup alerts for AWS billing](https://www.youtube.com/watch?v=O0sofGVT7uw)

## My Setup

I like the aspect of being notified of my cloud environment to have a pulse on what's going on - from resource health to costs. For my setup I ensured I attacked it from all angles. After I created my budget I added the following alerts: 
- When my **actual cost** is greather than 85%, I get notified
- When my **actual cost** is greater than 100%, I get notified
- When my **forcasted cost** is greater than 100%, guess what, I get notified

## Now, The Fun Part

Now that my budget has been created and I have alerts, it's time to have fun and start building!
