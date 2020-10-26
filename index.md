---
layout: default
title: PLUG | Portsmouth Linux User Group
---
<div>
	<h1 class="centre">Welcome to <span class="blue">PLUG</span> - <span class="blue">P</span>ortsmouth <span class="blue">L</span>inux
		<span class="blue">U</span>ser <span class="blue">G</span>roup</h1>
	<h4>Portsmouth &amp; SE Hants LUG is a group of individuals with a common interest in Linux &amp; Open Source software.</h4>
	<p>We hold regular monthly meetings (third Saturday of the month) where anyone is welcome to come along. At these meetings you can
	learn more about Linux and open source software, get help installing and using Linux, or join in discussions on open source and
	other IT related issues.</p>
	<p>Whether you are exploring Linux on the Raspberry Pi, learning about the Linux desktop or working with Linux on a server come along 
	and find out more. We are welcoming to all abilities and areas of interest whether you are a computer or Linux novice starting out, a 
	Raspberry Pi or hardware hacker exploring the GPIO, systems administrator looking after network services or a desktop Linux user 
	enjoying the freedom of open source come and share your experiences.</p>
	<img style="width: 320px; hieght: 180px;" class="imageright" src="/images/meeting.png" alt="PLUG Meeting">
	<h3>Monthly Meetings</h3>
	<p>Meetings are held at 1pm on the third Saturday of every month. Confirmation of dates and other information about our meetings
	are announced on the mailing list. We endeavour to have a talk every month, to see what we have had in the past and what is
	planned take a look at our <a href="/talks/">talks page</a></p>
	{% for item in site.data.nextmeet %}
	<h4>Next Meeting: 1pm Saturday {{ item.date }} {{ item.month }} {{ item.year }}</h4>
	{% endfor %}
	<h4>Venue: <a href="/venue.html"> Broad Oak Sports &amp; Social Club - Hilsea</a></h4>
</div>
<div class="centre">
	<p>Join the <a href="/mailing_list.html">mailing list</a> and start talking with other Linux users in Portsmouth and surrounding
	areas.</p>
</div>
