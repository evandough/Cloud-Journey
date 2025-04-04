# Microsoft Entra Multifactor Authentication (MFA)

## Introduction

Security is more important as it's ever been and it's crucial to add an extra layer of security. MFA allows an additional form of identification. 

## Prerequisite

Here is a [LINK](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-mfa-howitworks) for more information on MFA and how to setup MFA in your own Azure account.  

## Implementation of MFA

To enhance account security, I enabled Multi-Factor Authentication (MFA) on my **Azure** account. I downloaded the Microsoft Authenticator app onto my cellular device, linking it via QR code. After verifying successful authentication, I tested login scenarios to ensure proper enforcement. This setup adds an extra layer of protection against unauthorized access, especially for privileged operations and portal access.
<br></br>
I also utilized MFA on my **AWS** account. There's something about a bit of extra security that helps one sleep at night. 
<br></br>
There was a client who enforced MFA on their **WordPress** site - this was brilliant because if you didn't setup MFA once you logged in, it would cut off your access after a certain period of time. We'll call this client **Mildred**, and believe me, you don't want to let **Mildred** down...setup MFA, create a work ticket if needed, just get it done. 

## Next Steps

Going back to helping one sleep at night, the next steps would be to create policies within your cloud provider. If you've ever read an IT Reddit post or seen an IT meme, you've heard stories of large bills you accidentally accrued. 
<br></br>
Next step policy ideas would be: 
- deny massive-cost VM SKUs
- require tagging
- restrict resource creation to certain regions
