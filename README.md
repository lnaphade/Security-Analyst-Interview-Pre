# Security Analyst-Interview preparation

# DOM-based XSS vulnerabilities 
```
DOM based XSS vulnerabilities lies in client-side Injection. The client-side scripts within an application's response reads data from an attacker controllable part of the DOM (for example,
the URL), and writes this
Data into the HTML document in an unsafe way. An attacker may be able to use the vulnerability to construct a URL which, if visited by another application user, will cause JavaScript code supplied by the attacker to execute within the user's browser.
Its not possible to prevent DOM Base XSS from Service.
Firist Thing To do is to find  vulnerable dom pages and parametrs and Value in order to construct a URL
Let say I have found some sample web page let call www.test.com/defaul=



A DOM based XSS vulnerability arises when the DOM is used to generate dynamic content containing user input that can be processed without checking. This kind of attack is carried out with JavaScript in the user’s browser. Here the locations that (malicious) user input bring into the DOM are designated as source. The locations in which (malicious) user input can be executed
in the DOM are designated as sink.
```
