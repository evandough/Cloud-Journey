# AWS Multi-factor authentication in IAM

## Introduction

I've been wanting to create a **WordPress** website hosted in **AWS Lightsail** for some time now and decided to take the plunge. First things first - I need to setup an **AWS** account!
<br></br>
I though back to when I documented [day 3 - Microsoft Entra ID MFA](https://github.com/evandough/Cloud-Journey/blob/main/Journey/003/Readme.md) and wanted to ensure I slept well at night knowing there was an extra layer of security, so I implemented MFA on my **AWS** account as well. 

## Implementation

Once the **AWS** account was setup I followed [THIS AWS DOCUMENTATION](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa.html) to implement MFA.

## Testing to Verify

Once MFA was implemented, to test I logged out and logged back in and **VOILA!** I was prompted to use MFA to log in!

## Next Steps

This is where the fun begins - I can now create a **Lightsail** instance, setup networking, manage DNS, create snapshots, test backups by creating new instances based on snapshot, etc., etc. This goes beyond **Lightsail**, because now we've opened the door to two cloud providers to build, test, and deploy a variety of resources. 
