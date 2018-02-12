# SWGOH.GG Public Repo

Updates: https://updates.swgoh.gg/

### Where's all the code!?

Unfortunately, SWGOH.GG's codebase is not public. This repo exists as an issue tracker and a place for general information about the site.

### Who makes this site?

The site was started by [sanktanglia](https://github.com/sanktanglia) and [danpaulson](https://github.com/danpaulson). After the launch of mods, [scoot1585](https://github.com/scoot1585) and [drdemp72](https://github.com/drdemp72) joined the (unofficial) team. That is the team to this day.

### Is there an official SWGOH.GG API?

Currently there is no official API, though you may find some around the site that we use. Our intention is to release an API that can support third party sites, but there are some technical hurdles we need to overcome first.

### FAQ
* **Can you add data for partial shard counts on Player's Units?**

  No. Unfortunately, this data is not exposed to us currently.
* **My account is not syncing at the correct time!**

  While we can assign when to *start* syncing your profile, we cannot assure that it will be sync'd at a certain time. Some payouts include 30,000+ accounts, and take over an hour to process them all. This could be improved with refactoring and more resources in the future, but will never be eliminated.

* **I got a 402 Payment Required! Where do I sign up!?**

  This was just our way of ratelimiting calls - we do not have a premium / paid for service. As we continue to work on the API, we will expose the limits and implement a program to allow approved developers to increase them.
