
```
Red Teamers need to be agile and dynamic. If intel can help an organization blacklist a C2 server before the first phishing e-mail is even sent, that's GOOD INTEL.

As a Red Teamer, we should not be dependant on any one framework or technology. We should have extra tooling in our back pockets to adapt.

I see too many "Red Teams" who are simply obtaining tools, and running them. An adversary is not going to just run a tool and hope for the best.

Back to the point, I've also found "Red Teams" running C2 with invalid certificates, and using domains with no reputation. Many of us in the community have been doing it "right", and we take the "correct way" to do attack simulations for-granted. My survey suggests that there are many "Red Team" shops out there that just have no clue what's happening.

Red Teamers need to stop thinking of attack simulations as a 1-on-1 fight against an organization. In a real scenario,
the blue team most likely has shared intel resources with partner organizations. Defense was never a solo fight against the dark
```
# Red Team Tradecraft
```
Once I have a foothold, my first goal is to elevate privileges.I Use PowerUp script. To  misconfigurations  

Once I elevate, one of my first priorities is to move away from patient zero (the initially compromised system). 
My options to move are dictated by the trust relationships I have access to. Now that Beacon has hashdump and wdigest, 
I run these commands as soon as I have the necessary privileges.I also use ps to see which processes are running as users other than my current one.

#Lateral Movement
to find my potential lateral movement targets.To discover targets, I use Windows net commands and Ping sweep, identity as another user, I usually try to steal an access token from another process
If I know credentials, I use net use to connect to C$ or admin$ on a remote system.
```
# What is a Red Team Engagement
```
A red team assessment is a goal-based adversarial attack simulation to measure How organization would respond to a
multi vector attack and how ability to detect and respond to a realworld attack scenario.
The Goals for the engagement are defined Before Execution the assessment such as Credential Collecting , gaining internal network access,Gaining access to Domain Controller 
and having access to confidential data and documents By Compromising Report Server During the engagement.
```
