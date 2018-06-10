---
layout: project_details
title: RegTop
subtitle: A webapp which helped NU students register their project topic on first come first serve basis while taking care of topic similarity
test_cases: None
code_quality: Bearable
commit_activity: None
breadcrumbs: ["screenshots"]
permalink: /regtop/

---
<div class="content" markdown="1">

A webapp which helped NU students register their project topic on first come first serve basis while taking care of topic similarity at the same time.

If the proposed topic matches to a high degree then the user is warned and if the student continues ahead with that topic then that topic is flagged and the final decision lies with the professor.
If the topic is not highly similar to already registered topics then user can register their topic.
###### Approach:
- Assumed that similar project will have similar names thus only parameter used to check similarity was a string i.e. project's topic, the procedure runs through the database and returns the highest matching topic.
- The criteria of string's similarity is how many characters have to be inserted/replaced and/or rearranged to make the two strings equal.
- The threshold was 75% ie if the topic matched more than 75% to existing topic , it is highly likely it is similar in "human terms" also.
- White spaces and special characters were ignored.

---

## Screenshots

</div>

<figure class="image is-16by9">
    <img src="/img/regtop/landscape/0.png">
</figure>
-
<figure class="image is-16by9">
    <img src="/img/regtop/landscape/1.png">
</figure>
-
<figure class="image is-16by9">
    <img src="/img/regtop/landscape/2.png">
</figure>
-
<figure class="image is-16by9">
    <img src="/img/regtop/landscape/3.png">
</figure>
