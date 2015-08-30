# My Azure Mobile Service
Handy information about my mobile service at Azure.

<h3>Service URL</h3>

https://sirarsmobileservice.azure-mobile.net/

<h3>Git Repo</h3>

https://sirarsmobileservice.scm.azure-mobile.net/sirarsmobileservice.git

<h3>Scheduler Job Scripts</h3>
All scripts are written with node.
<h4>email_sender_phone_raspi.js</h4>
Checks the heart beat of https://raspi.sirars.com/. If status code != 200 or request error, then an e-mail and SMS is sent to me.
<br />
<h4>if_hackathon_2015_tweet_it_read_it.js (disabled)</h4>
Twitter bot created as a proof of concept during the If Skadeforsikring Hackathon 2015. The bot uses its own Twitter account (@IfHackathon2015) and if you ask it the right question by direct message, it will respond to you. 
<br />
<h4>nnug_oslo_twitter_bot.js</h4>
Twitter bot that tweets on behalf of @NNUGOslo. Requests data from http://www.meetup.com/nnugoslo/ and tweets upcoming events periodically. In addition, requests data from https://vimeo.com/nnug and tweets recently added videos periodically.
<br />
<h4>nnug_twitter_bot.js</h4>
Twitter bot that tweets on behalf of all NNUG chapters. Requests data from all the NNUG meetup sites at http://www.meetup.com and tweets upcoming events periodically. In addition, requests data from https://vimeo.com/nnug and tweets recently added videos periodically.
