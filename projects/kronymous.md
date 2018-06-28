---
layout: project_details
title: kronymous
subtitle: A Chrome app which creates a system wide (tor)socks proxy enabling access to Tor network
test_cases: None 
code_quality: Bearable
commit_activity: Occasional  
breadcrumbs: ["screenshots"]
permalink: /kronymous/
redirect_from:
  - /current_projects/details/kronymous/
  - /krotor/
---


<div class="content" markdown="1">

A Chrome app which creates a system wide (tor)socks proxy at port 9999 enabling access to Tor network.

**Earlier this app was titled KroTor, the name was changed to Kronymous to comply with Tor trademark rules.**

The app runs in secure sandboxed environment provided by Native client on Google Chrome or Chrome OS.

[Native Client](https://developer.chrome.com/native-client){:target="_blank"} is a sandbox for running compiled C and C++ code in the browser efficiently and securely, independent of the user’s operating system.

The Tor's core code and libevent(Tor's dependency) were ported to make them work in Native Client environment(this was done as part of my [Google Summer of Code 2015 project](/gsoc), the help provided by the mentor was critical in making this all possible).

The compiled C code can be run in Chrome which provides the same functionality as the Tor running in the native OS(viz. linux, windows etc).

Later, after testing on different systems and making it more user friendly(GUI was designed by [Puranjay Jain](https://github.com/puranjayjain)).  
This app was released on webstore and at it highest had 28K active users.

**[Code available on Github.](https://github.com/codebuff/kronymous)**  

Google has deprecated the Portable native client platform in favor of WebAssembly thus no new development is being done on this project and is not maintained.  
 
---
    
## Screenshots 
    
    
</div>


<figure class="image is-16by9">
    <img src="/img/kronymous/landscape/0.jpg">
</figure>
-
<figure class="image is-16by9">
    <img src="/img/kronymous/landscape/1.jpg">
</figure>
-
<figure class="image is-16by9">
    <img src="/img/kronymous/landscape/2.jpg">
</figure>
-
<figure class="image is-16by9">
    <img src="/img/kronymous/landscape/3.jpg">
</figure>
-
<figure class="image is-16by9">
    <img src="/img/kronymous/landscape/4.jpg">
</figure>






