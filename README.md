concrete5 is a powerful CMS built around the idea of in-context editing. It's a mature product with lots of IO, so there's lots of opportunities to find less than perfect code. ;) 

Read This
=========
* __IMPORTANT: DO NOT TEST concrete5.org.__ Do not test an install of concrete5 that you do not own. This includes concrete5.org and any other existing install you might find. If you report an issue against concrete5.org or another install you do not own, it will not be accepted. Instead, install a local copy of concrete5. This will let you test concrete5 without disrupting other users.
* __IMPORTANT: SERVER CONFIGURATION ISSUES DO NOT QUALIFY.__ Do not report configuration issues with concrete5.org, portlandlabs.com, etc. For example: software versions, SPF headers, etc. These are outside of program scope. The goal of this program is to find vulnerabilities in the concrete5 CMS software itself.
* For instructions on installing a local copy of concrete5, see the [Installation Guide](http://www.concrete5.org/documentation/developers/5.7/installation).
* We receive many reports from researchers who do not read these rules. To prove that you've read and understood these rules, please include the word "crayons" somewhere in your report. If you do not, your report will be closed as invalid.

Requirements
============ 

* Test on your copy. We're open source, so [grab a copy from our site](http://www.concrete5.org/developers/downloads/) and [install it locally](http://www.concrete5.org/documentation/developers/5.7/installation). Beating on our trial servers or concrete5.org will not be well received.
* Be clear. We totally get that you're not paid to do this. Here's a coincidence, neither are we! There's no huge corporate benefactor behind concrete5 today, so we're not in a position to 
ponder your terse report that's steeped in insider snark to guess at what you meant. You spent the time finding the issue, muster an extra 2 minutes to spell out what you're able to do with it 
so us over allocated curmudgeons understand the severity of our screw up. ;)
* Be responsible. We're here because we want to know vulnerabilities before the world does so we have a chance to provide a solution in a reasonable timeframe. We assume you're here for the 
same. Report issues directly to us here.
* Addon's and Themes for concrete5 should not be reported here, you should contact the author of the code.
* 3rd Party Stuff. We use jQuery, ADODB, TinyMCE, some Zend Libraries, etc.. If you find an issue entirely within one of our included solutions, we're of course interested, but likely only if 
they lead to severe/critical issues (below)
* For issues affecting only concrete5.org or other sites run by Portland Labs, please email security [at] concrete5.org with a detailed report.

Levels of Severity
======
* __A severe issue__. Someone with no access can get editor/admin access to a concrete5 site when they should not. This is a huge deal and we will be all over it.
* __A critical issue.__ Someone with no access can do something that might impact someone who does have access. (IE: SQL injection from a form anyone can get at)
* __A medium issue.__ Someone who already has editor/admin access can do something they shouldn't. Typically it's SQL injection or cross site scripting vulnerabilities but they require you already 
to have access to the dashboard. Being able to get a level of access greater than what you are supposed to have would likely graduate a vulnerability into a critical or severe issue in our eyes.
* __A minor issue.__ Something that's less than ideal, but can't be used to do anything nefarious today. Things that only impact the browsing experience of the person attacking likely fall into this 
category.

Response
=======
* We will respond to most reports within 48 hours.
* We will fix ___severe___ security issues within 48 hours of confirming them, all other issues will be fixed within a reasonable timeline as determined after triage.
* We've got swag and honor for those who submit issues, but no cash. Type of swag will be determined on a case to case basis.


(Big thanks to Phabricator for help with this glorious wall of text)
