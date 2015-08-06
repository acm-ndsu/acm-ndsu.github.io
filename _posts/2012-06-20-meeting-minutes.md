Due to several officers having other obligations, we did not have an EC meeting this week. However, we did exchange some email.

<b>Cesar:</b>
First, I finished adding all the business to the database but I still need to finish adding some contacts. It took me around an hour but I am done with 80% of the contacts, I will finish the other 20% over the weekend. I prioritized the business that we have had more contact with and the one that are located close to Fargo too. 

I also went over some of the VistaPrint samples and we should be good to decide into a predefined layout and color and place our 250 free cards. They also have 250 premium business cards for 10$, I don't know exactly what is the difference(probably the paper and the designs we are allowed to use) but it is another option too.

I also received the password from Nathan to submit our 2011-2012 report. For finishing  it I will need some info, so tomorrow I will go to the ACM to finish with that.

Zech, you may be recieving an email soon from Joseph Arner, he is from ITS and he wants to contact you about confirming some information of the five servers we have at the ACM.

<b>Zech:</b>
<ul>
<li>Updated the business contacts web interface:
<ul>
   <li>You can now edit existing contacts, save or cancel the changes, and delete the contact.</li>
   <li>The edit/save/delete/cancel buttons now have nice mouse dialogs.</li>
   <li>Removed the alert window that would pop up every time a contact was saved.</li>
   <li>TODO:
       <ul><li>Add functionality to add a contact in the overview page.</li>
       <li>Cleanup the businesses page so a drop down shows up.</li>
    </ul></li>
</ul></li>

<li>Worked on the new servers:
   <ul><li> As a recall, what we want to do is to do all of our web hosting on melt, but keep the acm site and sig sites on buzz.
      <ul><li>Hosted sites should be located at ndacm.org/hosted/SITE.  I was also thinking about making another virtual server on buzz so that hosted sites would be http://h.ndacm.org/SITE. The shorter URL would be a plus, and it might be easier to configure.</li>
      <li>To do this, we need to use apache's mod_proxy so that content from melt looks like it is being served by buzz (ndacm.org) in a user's browser.</li></ul></li>
   <li>Once I have gotten this feature working, I will transfer over all of our hosted sites and we can finally retire the old buzz. (yay!)</li>
   <li>I may create a couple virtual machines that the thin clients can connect to - assuming Adam was okay with us using the thin clients in the office.</li>
   <li>I tried upgrading the new buzz and melt to 12.04 LTS today... It failed.
      <ul><li>Post update and reboot on melt, the filesystem was mounted read-only. I tried rebooting, and it fails to boot - can neither ping nor ssh melt now.</li>
      <li>I've updated and rebooted the new buzz, and I'm seeing the same symptom that the filesystem is mounted read-only. I'm afraid to reboot now, so I'll try to get to the bottom of the issue. It could be something that got messed up on vhost.</li></ul></li></ul></li>

<li>I postponed the event calendar additions for a later time. I might add some things to it before next week's meeting.</li>
<li>I might start on the ACM Alumni application this week. I'm thinking about checking into enyo - a javascript framework - to do this. I don't know much about enyo, so we'll see if it's viable.</li>
<li>Cesar, do you want to do the national report tomorrow at 18.00 CST?</li></ul>