---
layout: project_details
title: Intentio
subtitle: An android application intended for NU students
test_cases: None
code_quality: Bearable 
commit_activity: None
breadcrumbs: ["notes", "screenshots"]
permalink: /intentio/

---

<div class="content" markdown="1">
    


An android application intended for NU students.  
 - Imports (parses) the entire week’s timetable from the excel file (provided by university’s ERP).
 - Displays the daily schedule in more intuitive manner.
 - It calculates and displays next class, also provides notification 10 minutes before the class.

**[Play Store Link ](https://play.google.com/store/apps/details?id=net.codebuff.intentio)**  
**[Code available on Github ](https://github.com/codebuff/intentio)**

---

## Notes

Apache POI was used to parse excel file.

Currently the app supports only binary excel files (excel format 97-2003),
adding support for the newer excel files would bloat the app too much,
ultimately the aim would be to delegate this task to University's ERP,
which then can send the timetable in easier format ie json or ical format and then the app can just fetch the data in background.

---

## Screenshots
    
</div>

<div class="columns">
    <figure class="image column is-half">
        <img src="/img/intentio/portrait/0.png">
    </figure>
    <figure class="image column is-half">
        <img src="/img/intentio/portrait/1.png">
    </figure>
</div>
<div class="columns">
    <figure class="image column is-half">
        <img src="/img/intentio/portrait/2.png">
    </figure>
    <figure class="image column is-half">
        <img src="/img/intentio/portrait/3.png">
    </figure>
</div>
