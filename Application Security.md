# Security Analyst-Interview preparation

# DOM-based XSS vulnerabilities 
```
DOM based XSS vulnerabilities lies in client-side Injection. 
The client-side scripts within an application's response reads data from an attacker controllable part of the DOM (for example,
the URL), and writes this
Data into the HTML document in an unsafe way. An attacker may be able to use the vulnerability to construct a URL which,
if visited by another application user, will cause JavaScript code supplied by the attacker to execute within the user's browser.
Its not possible to prevent DOM Base XSS from Service.
Firist Thing To do is to find  vulnerable dom pages and parametrs and Value in order to construct a URL
Let say I have found some sample web page let call www.test.com/defaul=

A DOM based XSS vulnerability arises when the DOM is used to generate dynamic content containing user input that can be processed without checking. This kind of attack is carried out with JavaScript in the user’s browser. Here the locations that (malicious) user input bring into the DOM are designated as source. The locations in which (malicious) user input can be executed
in the DOM are designated as sink.
```

# Blind SQL Injection
```

Blind SQL Injection is a type of SQL injection that asks the database true or false questions and determines the answer based on the application’s response.
Other type of SQL Injection are easy to identify by submitting specific payloads. 
the server responds with error messages from the database server complaining that the SQL Query's syntax is incorrect if applications is vulnerable to SQL Injection. 
Blind SQL Injection attack more difficult to identify  than any other type of SQL Injection because the Database server do not responds with error messages by submitting specific payloads.
We can Only verify speficy application whethervernerable  Blind SQL injection or by submiiting  true or false. 1 ' 1=1

1 ' and 1=1 true
1 ' and 1=0 fue

```
# Insecure Direct Object References

```
According to the Open Web Application Security Project (OWASP), an insecure direct object references vulnerability is commonplace and easy to exploit
The insecure direct object references vulnerability allows an attacker to steal other users’ data of a specific type. According to My experience Application often use   key /value of object,and fail to check if user is authorized to modify it.
in consequence of existing insecure direct object references, Its possbile to  change other user data or delete user  account and change user profile something like that

```

# What is your Strengh
```
One of my greatest Strengh is that I am a fast learner and passionate about Cyber Security and keeping up to date new technology and Red Team techniques such AV bypasing and lateral movement techniques In order to used In realy Life infrastructure
I have the right combination of skills and experience for 
```
# What is your weakness
```

I am naturally shy. I have trouble speaking in group of people even though I have a good idea.   but I feel nervous when asked to present to a alarge group of people. 
But I know I need to be improve this area. Being Secuirty Consultant,My other Weaknesses is that I stammer when  I feel nervous.
```

# Mobile Application accessments
```
the purpose of bypassing Android SSL Verification and Certificate Pinning is  to intercept  and modify the mobile application Request  and to understand how application communicated with Server and How application access Data and Manged it.
One of my favorites method To bypass Android SSL Verification and Certificate Pinning is to perform manually 

First Step is to decompile The Taget file using apktool to put Custom Certitificate where located Certs folden

The next step is  to recompile using APKtool 

The Final Step is  Signing the Apk File using  SignApk Application ,Applications cannot installed on the device if application is signed.


First Step is to decompile The Tagget file using apktool  in order to understand the internal application functionality and look up sensitive information  such as cryptoapi private key and User credentials that Developer could be putted in the source code.
The next step is to conduct Dynamic Analysis,The purpose  of dynamic analysis is to  find security vulnerabilities or weakess when Application is running. Dynamic analysis is conducted both at the mobile platform layer and against the back-end services and APIs,
This step also Involve  to check for security mechanisms like authentication and authorization issues
```
# What is XXE
```
An XML External Entity vulnerability (abbreviated XXE) is an attack against an application parsing XML input from an unreliable source.
It’s usually caused by a misconfigured XML parser.One of the most common ways of finding an XXE is  upload function and a POST request carries a XML.
This attack possible  lead to the disclosure of confidential data, port scanning and Readable System file by everyone.
```

# Red Team
```

Red Teamers need to be agile and dynamic. If intel can help an organization blacklist a C2 server before the first phishing e-mail is even sent, that's GOOD INTEL.

As a Red Teamer, we should not be dependant on any one framework or technology. We should have extra tooling in our back pockets to adapt.

I see too many "Red Teams" who are simply obtaining tools, and running them. An adversary is not going to just run a tool and hope for the best.

Back to the point, I've also found "Red Teams" running C2 with invalid certificates, and using domains with no reputation. Many of us in the community have been doing it "right", and we take the "correct way" to do attack simulations for-granted. My survey suggests that there are many "Red Team" shops out there that just have no clue what's happening.

Red Teamers need to stop thinking of attack simulations as a 1-on-1 fight against an organization. In a real scenario,
 the blue team most likely has shared intel resources with partner organizations. Defense was never a solo fight against the dark
 ```
 # Cross-Site Request Forgery
 ```
Cross-Site Request Forgery Vulnerability attack against An application.
Attacker Trick victims to Click The malicious link deliver By Attack which containing Request to Application what to do.
Attacker Action is complete when Victims clicked The malicious link. 
```
 
