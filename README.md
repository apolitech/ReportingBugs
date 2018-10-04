
<html>
<head>
<meta http-equiv="content-type" content="text/html; charset=utf-8">
<meta name="generator" content="ReText 7.0.3">
</head>
<body>
<h1><strong>How to report bugs</strong></h1>
<p>Ubuntu uses Launchpad to keep track of bugs and their fixes. This page will guide you through the steps required to file a good and detailed report.
      Create a Launchpad account
If you don’t already have one - you need to <a href="https://login.launchpad.net/+login">create a Launchpad account</a>. This will allow you to file new bugs and comment on existing ones.</p>
<img src="https://github.com/apolitech/ReportingBugs/blob/master/launchpad_new_acc.gif?raw=true">
<p><strong>Determine if the bug is really a bug</strong></p>
<p>Before doing all this please use the <a href="https://ubuntu-mate.community/">Ubuntu Mate forum</a> and see if there are other users having the same problem. It can be instances when the problem is when a installation gone wrong or of a specific PC/Laptop configuration.</p>
<img src="https://github.com/apolitech/ReportingBugs/blob/master/forum_suport.gif?raw=true">
<h3><strong>Perform a survey of your problem</strong></h3>
<p>First, check the <a href="https://ubuntu-mate.org/blog/">release notes</a> of your supported version of Ubuntu Mate for any known issues from here. Second, check <a href="https://bugs.launchpad.net/ubuntu-mate">Launchpad</a> for any duplicates, and make note of this.</p>
<img src="https://github.com/apolitech/ReportingBugs/blob/master/release%20notes%20and%20Launchpad.gif?raw=true">
<p>(Reporting non-crash hardware and desktop application bugs
The method for reporting bugs in Ubuntu is by using the tool “ubuntu-bug”, otherwise known as Apport.) </p>
<hr>
<h2><strong>Reporting a problem in Ubuntu Mate</strong></h2>
<h3>If you know the program package name.</h3>
<pre><code>Press Alt+F2 and type ubuntu-bug x (where x is the name of program)
</code></pre>
<img src="https://github.com/apolitech/ReportingBugs/blob/master/ubuntu-bug%20x.gif?raw=true">
<hr>
<h3>If you want to Collect information about a program with a window open</h3>
<pre><code>Press Alt+F2 and type ubuntu-bug -w
</code></pre>
<p><u>(After you close the dialog the next window that you click on will have a problem report created for the package that created the window.)
<img src="https://github.com/apolitech/ReportingBugs/blob/master/ubuntu-bug%20-w.gif?raw=true">
</u></p>
<hr>
<h3>If you want to Collect information from a currently running program</h3>
<p><u>(To file a bug against a program that is currently running, open the System Monitor application and find the ID of the process.)</u></p>
<pre><code>Press Alt+F2 and type ubuntu-bug  xxxxx   (where x is the  process ID)
</code></pre>
<img src="https://github.com/apolitech/ReportingBugs/blob/master/ubuntu-mate%20xxxx.gif?raw=true">
<hr>
<h3>If you have a hardware issue or don't know the name of the program affected</h3>
<pre><code>Press Alt+F2 and type ubuntu-bug
</code></pre>
<img src="https://github.com/apolitech/ReportingBugs/blob/master/ubuntu-bug.gif?raw=true">
<hr>
<p>After running one of the above commands, Ubuntu Mate will gather information about the bug. This may take a few minutes. Review the collected information if you wish. Click <em>Send</em> to continue.</p>
<img src="https://github.com/apolitech/ReportingBugs/blob/master/collecting.gif?raw=true">
<p>A new web browser tab will open to continue processing the bug data. Ubuntu Mate  uses the website Launchpad to manage its bug reports.
After logging in to Launchpad, enter a description of the problem in the summary field.</p>
<p>After clicking Next Launchpad will search for similar bugs in case the bug you are reporting has already been reported.
If the bug has already been reported, you can mark that bug as also affecting you. You can also subscribe to the bug report to receive updates about progress with fixing it.
If the bug has not already been reported, click No, I need to report a new bug.</p>
<hr>
<h3>Fill in the description field with as much information as you can. It's important that you specify three things:</h3>
<p><strong>What you expected to happen</strong></p>
<p><strong>What actually happened</strong></p>
<p><u>If possible, a minimal series of steps necessary to make it happen, where step 1 is "start the program"
</u></p>
<p>Your report will be given an ID number, and its status will be updated as it is being dealt with. Thanks for helping make Ubuntu Mate better!</p>


<p> This documentation is an updated version of https://help.ubuntu.com/community/ReportingBugs and https://help.ubuntu.com/stable/ubuntu-help/report-ubuntu-bug.html.en </p>
</body>
</html>
