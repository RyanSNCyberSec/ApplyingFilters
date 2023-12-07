<h1>Filtering dates and numbers in SQL </h1>

 

<h2>Description</h2>
In this scenario, I investigated a recent security incident. Here I will demonstrate how I gathered information about login attempts for certain dates and times as this will help in resolving the security incident.
<br /> .


<h2>Languages and Utilities Used</h2>

- <b>MariaDB shell</b>
- <b>SQL</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Program Walk-through:</h2>

<p align="center">
Retrieving login events made after a certain date: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/SQL%20filtering%20query%202.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Expanding the date range to include 2022-05-09 in the search: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/SQL%20filtering%20query%203.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Narrowing the focus of the search to filter logins within a date range: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/SQL%20filtering%20query%204.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Investigating logins that were made at certain times: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/SQL%20filtering%20query%206.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Filtering login attempts based on event IDs within a narrowed-down range: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/SQL%20filtering%20query%208.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
