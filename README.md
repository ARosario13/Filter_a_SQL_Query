<h1>Filter a SQL query</h1>

<h2>Description</h2>
This was an instance where I was practicing filtering queries in SQL via a lab.
<br />

<h2>Environments Used </h2>

- <b>Windows</b>

<h2>Program walkthrough:</h2>

<p align="center">
I needed to get a list of all organization machines and their operating systems. First I ran a SQL query to retrieve only the device_id and operating_system columns from the machines table. First the string: <br/>
<a href="https://imgur.com/VhmRTE4"><img src="https://i.imgur.com/VhmRTE4.png" title="source: imgur.com" /></a>
  The results:
  <a href="https://imgur.com/Ab0LSBH"><img src="https://i.imgur.com/Ab0LSBH.png" title="source: imgur.com" /></a>
<br />
<br />
Next I needed to obtain a list of all machines with the 'OS 2' operating system because these machines need an update.
  <a href="https://imgur.com/fVdlKMJ"><img src="https://i.imgur.com/fVdlKMJ.png" title="source: imgur.com" /></a>
<p align="center">
After obtaining the results, I next needed to retrieve a list of all the employees in the Finance and Sales departments to obtain their office numbers. First the string:
<a href="https://imgur.com/N4JP4CB"><img src="https://i.imgur.com/N4JP4CB.png" title="source: imgur.com" /></a>
The results:
<a href="https://imgur.com/VkE7WQS"><img src="https://i.imgur.com/VkE7WQS.png" title="source: imgur.com" /></a>
<p align="center">
Now I needed to indentify employee machines. In the exercise, a machine in 'South-109' had an issue. I needed to determine which employee uses that computer so that I could send them an alert.
<a href="https://imgur.com/DJZt4mo"><img src="https://i.imgur.com/DJZt4mo.png" title="source: imgur.com" /></a>
<p align="center">
Next, I modified the query that I used in the previous step so that it returned information on all the employees in the 'South' building. First the string:
<a href="https://imgur.com/g7MmJ2T"><img src="https://i.imgur.com/g7MmJ2T.png" title="source: imgur.com" /></a>
The results:
<a href="https://imgur.com/hPd35Xc"><img src="https://i.imgur.com/hPd35Xc.png" title="source: imgur.com" /></a>

<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
