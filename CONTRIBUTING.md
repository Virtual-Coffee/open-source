# Virtual Coffee Open Source Contributions Guide

**Note:** this guide is intended for absolute beginners to collaborations on OSS projects, but we would absolutely love more experienced developers to read it and give feedback on how to improve!

## Getting Started

If you're looking to start learning how to work with the Virtual Coffee Open Source Repo, this doc tries to provide all the resources to get you from confusion to productivity.

We're not here to reinvent the wheel, so where we feel appropriate, we reference and link to resources we feel do a good job of helping a newbie through that particular section of setup.

Most of the project is currently written using [markdown](https://www.markdownguide.org/basic-syntax/) to make it easy to add, modify, and edit what we need to.

We try not to take anything for granted, but in case we miss something, please reach out to us in the Virtual Coffee slack group and let us know!

**Note:** If you're already in the Virtual Coffee slack, feel free to skip the section below and go straight to **Step 3: Find/Make An Issue**

## Step 1. Joining Virtual Coffee and the Slack

As of right now, there's no explicit restriction to who can contribute to this repo. However, we typically recommend that anyone wishing to contribute attend at least one Virtual Coffee Zoom meetup (you can find the meeting details [here](https://meetingplace.io/virtual-coffee)).

After attending the meeting, you're free to join the Virtual Coffe Slack group where attendees can chat and communicate in between meet-ups sessions. The slack is another great place for finding resources. Spefically, the **#open-source** channel is where we chat all things OSS, incluing contributions here, as well as other projects. If you've never used Slack before you can [learn about it here](https://slack.com/help/articles/115004071768-What-is-Slack-).

Once you've done that, you're good to go!

## Step 2. Setting up a Github Account

We're going to assume you know what [github](https://www.howtogeek.com/180167/htg-explains-what-is-github-and-what-do-geeks-use-it-for/) is about and how it works (otherwise, how would you be reading this?)

If you haven't made a github account as yet, make one [now](https://github.com). It's free!

## Step 3. Find/Make An Issue

Github uses a feature called _issues_. Issues are essentially a way to highlight bugs, features, problems, or any sort of suggestion or action you wish to happen on a github hosted project (you can find a more comprehensive explanation [here](https://guides.github.com/features/issues/)).

We highly recommend looking at the [Virtual Coffee open-source repo](https://github.com/Virtual-Coffee/open-source/issues) to find a good open issue to start with. We always try to keep them populated with some beginner friendly issues that anyone can attempt to solve. We also use a `PR Submitted` tag to indicate when an Pull Request has been submitted for an issue, but it hasn't yet been merged, as most people would rather would on an issue with no attempted PRs yet.

If you feel like there's a contribution you would like to make that isn't represented by an already existing issue, feel free to create your own!

## Step 4. Creating a PR
At this point, you have two options.

**The first option** is using the github interface to fork the repo and submit a Pull Request (no code or terminals or IDE required). [This guide](https://guides.github.com/activities/hello-world/) shows just how to do that for a small personal repo. You would simply replace the step of creating a new repository to just navigating to the virtual coffee open source one and forking that instead. This is a great idea if you simply plan to add to or edit one of the markdown files we use for documentation in this project.

**The second option** is go the traiditional route of forking the repo, creating a local copy of that fork, and working on your changes that way. This is also the only way to go if this project expands to include an associated application. For that we recommend [this guide](https://www.dataschool.io/how-to-contribute-on-github/).

If you want some additional tips before submitting a Pull Request, I recommend 

**Note:** The guide referenced above uses _master_ as the naming convention for the default branch in all its repos. Here at Virtual Coffee, _main_ is the default branch name. When following the instructions in the guide, simply replace _master_ with _main_ wherever it appears and it should proceed as normal. [this guide](https://www.hanselman.com/blog/EasilyRenameYourGitDefaultBranchFromMasterToMain.aspx) can help you transition with your own personal repos from master to main, and explains the methodology as to why you should.

## Step 5. Awaiting Review

Once you've submitted your pull request, the only thing left is to wait from feedback from one of the project maintainers. Since this is volunteer work for all of course, we ask for patience if you don't see a response immediately. Sometimes it takes about a day for someone's schedule to clear up to have the sit to properly review incoming PRs. We'd rather not rush a response after someone has put time and effort into submitted. If it's been over 24 hours and you haven't received any acknowledgement, you can post a message in the **#open-souce** channel in the slack reminded of your PR, and someone will get back to you.

If the PR looks good, a maintainer will typically give feedback and merge the request immediately, otherwise they'll let you know what questions they have or what needs to change before your work can be accepted. Once it is, you'll see your changes on the main branch and VOILA, open source contribution complete!

## Step 6. Tips, Tricks and Gotchas

This section is just little notes and bits of info that can smooth over some of the bumps and hiccups that can come along with contributiong.

- While this isn't absolutely required, we highly recommend **associating your Pull Requests with the Issue that they're intended to address**. This makes review much easier and avoids confusion when looking back at past commits. Github allows you to link a PR to an issue both during and after the PR's creation (the option should located in rightmost panel of the github PR interface).
- **Please do not hesitate to ask for help** in any part of this process if you feel confused. As soon as they can, project maintainers can try and get you through the parts which are confusing you. Just be aware that no one here is a github expert :), we're just folks happy and willing to help others get some experience.
- Be extra careful when working with git in the command line. Incorrectly typed names or commands can have strange results, and navigating git issues can be very perplexing. Fortunately, there's a plethora of resources on fixing said issues, and rest assured that any error you make has already been done, and solved, by someone already

That's all for now. If you feel like anything is missing from this document that you wish were included, let us know. Or hey, open up a fresh issue and take a shot at helping us make it better!
