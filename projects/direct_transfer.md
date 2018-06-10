---
layout: project_details
title: Direct Transfer
subtitle: An intrAnet file sharing application
test_cases: None
code_quality: Horrible
commit_activity: None
breadcrumbs: ["idea", "instructions","videos", "screenshots"]
permalink: /direct-transfer/
---

<div class="content" markdown="1" id="description">

An intrAnet file sharing application(utilizing Bittorent protocol). The application was ported from Vuze, GUI was highly simplified as well as many of the (unrequired)plugins and features were removed.

Once that was done, then the app was customized according to the needs, to read about that in details, please see [below](#idea).
##### The project was discontinued after release of second version since client isolation was implemented in the campus, making further development infeasible. For reason(s) check [below](#idea).

---

</div>

<div class="content" markdown="1">

## Idea   

During my stay in campus till now(second semester) I noticed a particular trend of downloading same file by every
person individually which uselessly occupies university’s internet bandwidth.
We have a robust network, so if there is a file inside campus then it can be shared inside intranet itself, as we already have necessary infrastructure for it, only thing needed is a tool and method to implement it.

**I had two different ideas about the way to implement this**

**First Method**
Creating a dedicated server which stores the list of user who wants to share the file along with file being
shared *No file is stored on the server*.
Client application makes query for a file and if file is available on intrAnet then the app creates bridge between those two devices and file is sent from file host’s device to requester’s device
*Main pros of this method:* The website can be expanded to include intranet messaging ,calling etc by means of android apps etc and other features which I can add as and when I will get feedback from users.

**Second Method**

Only client application will be made which will send out a notification as soon as it is online on intranet(similar to upnp) and it will search all the devices on intranet which have the app online and retrieves the list of file which users are willing to share and makes query and if file is found and allowed to be shared the app creates
bridge between those two PC and file is sent from file host’s device to requester’s device.



**In the implemented method** the client app behaved as the tracker (also), this was possible only because the IPs of devices inside the network were reachable/discoverable by others.(*if not in the entire network then atleast in the subnet*.)
However since UDP has the tendency to flood the network and their was a possibility of security breach, the further development was discontinued after the successful run for the first two version.

Client isolation was implemented in the campus(in 2013), which meant that IPs inside the network were not reachable/discoverable anymore thus sending file from one device to another became almost impossible.

For demo videos and screenshots please scroll [down](#videos).

---
</div>

<div class="content" markdown="1">

## Instructions

*These are applicable on both linux and PC version*

1. Click file in menu bar > Transfer Privately
*here is the explanation of four options*
- File(share a single file)
- Folder (one 'share' is created containing everything in the folder)
- Folder's contents (each item in the folder is shared as a separate item) and
- Folder's contents recursively (each item in the folder is shared if it is a file; if it is a folder then each item in that folder is shared and so on).
2. Choose your preferred option.
3. Select the file/folder you want to share.
4. After app has successfully seeded the files.
5. Right click the entry > advanced > export > torrent
in the following dialog box which opens up save the file as name.torrent on desktop (or any convenient place ).
6. Send this torrent file to anybody you want to share with (size of this file will be around 2/3  kb so don't worry).
7. The recipient can just add that file by double clicking or importing.
<hr>


## Videos

<iframe width="100%" height="520p"  src="https://www.youtube.com/embed/6UyitIRMB14"></iframe>

-
<iframe width="100%" height="520p"  src="https://www.youtube.com/embed/dnoLJPGoIMc"></iframe>

-
<iframe width="100%" height="520p"  src="https://www.youtube.com/embed/iqd1qBMEXX4"></iframe>

___



## Screenshots


<figure class="image is-16by9 is-marginless">
    <img src="/img/direct-transfer/landscape/0.png">
</figure>

-

<figure class="image is-16by9 is-marginless">
    <img src="/img/direct-transfer/landscape/1.jpg">
</figure>
</div>