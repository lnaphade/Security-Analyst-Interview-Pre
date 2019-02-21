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
```
