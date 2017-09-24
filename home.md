<!-- TITLE: Welcome to the IOTA Wiki -->
<!-- SUBTITLE: A knowledge platform for the IOTA ledger. -->

# What is IOTA?
???
# About this Wiki
After registering to the [iotatangle Slack](/community/slack) a few months ago I learned how difficult it is to find specific information in this environment designed for small teams. Developers and regular users provide very helpful answers to most of the questions, but especially new users joining the Slack have a hard time finding useful material in between the large amount of gossip, parrots and flashing HODL banners. All information is basically hidden from the public (from search engines too) and can't be shared with the people outside of Slack in a straightforward way.

We, the community should make IOTA more accessible for the large number of developers, researchers, journalists and people otherwise interested in this exciting technology. By creating a comprehensive, open knowledge platform we can reduce the number of (duplicate) questions while we prevent common errors and misunderstandings, accelerate growth and improve productivity and happiness of everyone.

The aim of IOTA Wiki is to collect and publish all the useful information about [IOTA](/iota) and [JINN](/jinn), their underlying [technology](/research), [ecosystem](/p) and [community](/community). All information belongs to the community and is backed up in a public [Git repository](https://github.com/iotapizza/iota-wiki).
# Usage and workflow
As a member of `iotatangle` you can [log in](/login) with your Slack account. If you don't want to use or disclose your Slack email address, send a PM with an email address (doesn't have to be working, but valid) to a [moderator](/wiki/moderators) and you will receive a password via PM. There are no other ways to register.

Users will be granted write permission only within their personal user section `/u/username` by default. The username is equivalent to their Slack usernames. In their `/u` sections users can publish pages with information related to IOTA and other things they want to share with the community and general public.

Then this project needs the help of as many users as possible to create main pages like:
* [What is IOTA?](/iota/about-iota)
* Download and install the wallet
* Securely create and store a seed

and many other guides, preferably in multiple languages too. For write requests and general discussion about this project I created the `#projectwiki` channel.

Write permission is individually assigned to users (or groups of users) who want to work on a specific page or section. This is necessary in order to prevent spam, if there were no restrictions some people would vanish content and put their reflinks and unrelated projects everywhere. We will assign moderators from different timezones to take care of the user permission management and to have an eye on the user activities.

The information will be grouped into sections like [/dev](/dev), [/research](/research), `/wallet`, `/spanish` (or simply `/es`)  and only selected users get write permission in each section. A specific group of users will be able to create and edit pages about `/research` aspects of IOTA, while `/wallet` guides can be managed only by wallet developers. (These pages contain sensitive data like download links and checksums.)

It would be great to see many different users here, especially those not having a technical background looking for a way to contribute. Grab the initiative and start to turn this wiki into an informational, educational and entertaining place for the entire IOTA community.
# Technical details
[IOTA Wiki](/wiki) is based on [Wiki.js](https://github.com/Requarks/wiki), a simple and very lightweight wiki engine which can be customized and extended to our needs easily. The entire content is archived in a [public repository on GitHub](https://github.com/iotapizza/iota-wiki) that keeps track of the changes too.

The wiki engine is hosted on servers of mine and the domain name `iota.pizza` in my private hands. I hope this project will continue to exist under an official hostname like `wiki.iota.org` once it starts to become a useful source. 

I intend to put more time into the project, to [debug](/wiki/known-issues) and [extend](/wiki/to-do) the wiki engine and to give it a unique look following the IOTA [design and color scheme](/dev/resources-designer#design-color-schemes). Take a look at the [wiki-engine](https://github.com/iotapizza/wiki-engine) repository or contact [me](/u/cymon) if you are interested to help.
# Get started
* Join the discussion in the  `#projectwiki` channel, bring in your ideas and help to shape this project.
* Read the [usage guide](/wiki/usage). Feel free to ask any questions on Slack or contact a moderator.
* You could start to create a page in your `/u` section about a topic not covered by the wiki yet. Ask other users for feedback and move the page to a proper section once you are happy with the result.
* There are many pages like [Presentations](/marketing/presentations), [Units & Supply](/iota/units-supply), [Snapshots](/dev/snapshots) and [Whitepaper](/research/whitepaper) that contain only very basic information. Ask for write permission in order to help improving these pages.
# Warning!
**Keep in mind that everything is synced to GitHub where the entire history of IOTA Wiki is permanently available for everyone! Each time you click the `save changes` button, the (edited) page is commited to the git repository. Think about the good and the very dangerous effects this can have and make sure not to post sensitive data like passwords and seeds!**