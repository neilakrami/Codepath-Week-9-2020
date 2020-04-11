# Codepath-Week-9-2020

6 hours spend in total
To find possible vulnerbalities

Username Enumeration
Insecure Direct Object Reference (IDOR)
SQL Injection (SQLi)
Cross-Site Scripting (XSS)
Cross-Site Request Forgery (CSRF)
Session Hijacking/Fixation

GREEN

Vulnerability 2 - Username Enumeration
Try logging into a real user's account with the wrong password, and you get a message in bold letters.
Log in with a random username and password, and you get a message which does not have bold letters.
An attacker can use this clue to find valid usernames.

https://user-images.githubusercontent.com/26352156/79035940-f631b980-7b77-11ea-8320-994647e72b2f.png

GREEN

Vulnerability 1 - Stored Cross Site Scripting Attack
Enter the following script into the feedback section of the public site: <script>alert('Nilab found the XSS!');</script>
Then log into the site and view the feedback.
The alert that pops up shows that a stored XSS attack has been performed.

 

