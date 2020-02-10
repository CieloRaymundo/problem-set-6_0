# Unit 6 Lesson 0 Problem Set

0. Describe, in as much detail as you can, what happens when you open up Google Chrome, type "marcylabschool.org" into the address bar, and press enter.
When you type "marcylabschool.org" into the address bar in Google Chrome, a request is being sent to the server as an ip address through http the DNS server then recieves this request and checks if it is available in this specific server. If it is not available in this server it will ask another server if it contains this address. Once it is found the server will then send  a response back resulting in the website loading
1. HTTP is a "stateless" protocol - what does this mean?
Stateless means that it doesn't save the previous action done by the client saved on the website. For every GET or POST response on the website being done there is no way to save it and keep track. 
2. Given that HTTP is a stateless protocol, how do we build "stateful" web applications.
In order to create a stateless web developers had to create ways to go around it, by using sessions and cookies. In a session the client sends a request to the server with a session id, which helps servers identify clients. Cookies are used to store browser data for the client stored in the server. This data is created in the request/response cycle between and client and server. 
3. What is the difference between HTTP and HTTPS?
HTTP is not encrypted while HTTPS is. 
4. Security is an important concept for web applications. What are two ways we can try to prevent a user's session from being highjacked?
We can either sanitize a users input or escape users input so that the webpage doesn't read it as code.
5. What is the Same Origin Policy? What about CORS? How are they related?
The same origin policy allows different address communicate with eachother if they have the same origin 
Ex:
    http://mysite.com/doc2 and http://mysite.com/doc1
Since they have the same beginning 
But not:
    http://mysite.com/doc1 and https://mysite.com/doc2
The first address doen't contain the "s" for security and the second address does, they don't have the same origin

CORS stands for "cross-origin resource sharing" which allows interactions made by different origind that the origin policy would typically not allow
6. Using cURL, make requests to http://www.reddit.com/r/programming and http://www.reddit.com/r/programming/.json from the command line. What differences do you notice between the two different response bodies? Why is this be significant?

7. What are request and response _headers_? Why are they important?
