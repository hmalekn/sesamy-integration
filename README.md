# Sesamy Authentication Platform

Have you ever wondered why we should be forced to use usernames and passwords? It doesn't make sense to remember a sequence of characters in order to authenticate to an application. 

There are solutions such as password generators and password managers, but they still rely on a master password. Multi-factor identification systems add value, but their workflow is either manual or complicated. Single sign-on is another option, but they are hard to adopt. All of the above solutions store your username and passwords and possibly your private information. They seldom are the target of cybersecurity attacks. That puts their users in the risk of losing their private information. 

Sesamy authentication platform once for all eliminates the risks associated with the username and password. Sesmay platform allows mobile users to authenticate to web, desktop, mobile, smart tv, and gaming consoles applications, or even IoT devices. You don’t need to enter or remember your usernames and passwords anymore, just point and scan the login page and use the fingerprint or face recognition to verify your identity. It’s secure and fast at the same time.

This video for example displays how a ServiceNow Service Portal instance have used the Sesamy Authentication platform:

[![Watch the video](https://img.youtube.com/vi/MuiJQYCeVKM/maxresdefault.jpg)](https://youtu.be/MuiJQYCeVKM)

# How to integrate?

- Contact us to receive a set of credentials for your application
- Call an API to get the authentication payload and the QR code for it
- Render the QR code on your login page
- Listen for the login authorization event on your client side
- Submit your login form to your server
- Pass the authentication payload to the authenticare API and get the user information
- Implement the user mapping logic on your server side and authenticate on behalf of the mapped user. 

# Sample code

We try to add sample applications for the supported platforms. We currently have a simple Node.js application that shows how a Node.js application should integrate with Sesamy platform.
