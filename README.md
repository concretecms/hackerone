concrete5 is a powerful CMS built around the idea of in-context editing. It's a mature product with lots of IO, so there's lots of opportunities to find less than perfect code. ;) 

Requirements
============ 

* Test on your copy. We're open source, so grab a copy from our site and install it locally. Beating on our trial servers or concrete5.org will not be well received. 
http://www.concrete5.org/developers/downloads/
* Be clear. We totally get that you're not paid to do this. Here's a coincidence, neither are we! There's no huge corporate benefactor behind concrete5 today, so we're not in a position to 
ponder your terse report that's steeped in insider snark to guess at what you meant. You spent the time finding the issue, muster an extra 2 minutes to spell out what you're able to do with it 
so us over allocated curmudgeons understand the severity of our screw up. ;)
* Be responsible. We're here because we want to know vulnerabilities before the world does so we have a chance to provide a solution in a reasonable timeframe. We assume you're here for the 
same. Report issues directly to us here.
* 3rd Party Stuff. We use jQuery, ADODB, TinyMCE, some Zend Libraries, etc.. If you find an issue entirely within one of our included solutions, we're of course interested, but likely only if 
they lead to severe/critical issues (below)

Targets
======
* A severe issue. Someone with no access can get editor/admin access to a concrete5 site when they should not. This is a huge deal and we will be all over it.
* A critical issue. Someone with no access can do something that might impact someone who does have access. (IE: SQL injection from a form anyone can get at)
* A medium issue. Someone who already has editor/admin access can do something they shouldn't. Typically it's SQL injection or cross site scripting vulnerabilities but they require you already 
to have access to the dashboard. Being able to get a level of access greater than what you are supposed to have would likely graduate a vulnerability into a critical or severe issue in our eyes.
* A minor issue. Something that's less than ideal, but can't be used to do anything nefarious today. Things that only impact the browsing experience of the person attacking likely fall into this 
category.

Response
=======
* We will respond to reports within 48 hours.
* We will fix ___severe___ security issues within 48 hours of confirming them, all other issues will be fixed within a reasonable timeline as determined after triage.
* We've got swag and honor for those who submit issues, but no cash. Type of swag will be determined on a case to case basis.
