{{TITLE:Contribute - Pinta}}
# Contribute

## Bug Reports / Feature Requests

One way to contribute to Pinta without writing code is to file bugs when things don't work.  Bug reports let developers know what needs to be fixed in Pinta.  Or if you have a great idea for a new feature for Pinta, we've got a place where you can submit your ideas and vote on which ones should be implemented.

* [Pinta Bug Tracker][1]
* [Pinta Feature Requests][2]

## Translations

Another way to contribute to Pinta without writing a line of code is to translate Pinta into a new language.  This is all done through a web page, so all you need to know is a second language.

* [Pinta Translation Page][3]

## Patches and Fixes

If you are interested in contributing to the core of Pinta, like to fix a bug or tweak existing code, you'll want to make your changes available as pull requests on GitHub. Using Git is an important part of contributing to Pinta, so if you want to read up on this we recommend reading the excellent documentation on GitHub, or if you want an even
deeper understanding read [Pro Git][4].

The source code for Pinta development is available on [PintaProject GitHub][5].

#### General recommendations

It is suggested to do small changes at first that you get familiar with the way project is operating. For instance look at the [easy to fix bugs][10]. Instead of creating one big fat change like 1000 lines of code change in one commit, please make several small changes and several commits that logically fit together. Please keep in mind, that all of the code has to be reviewed, understood and accepted by maintainer. There should be no hard fillings if maintainer rejects some of the code or requests to make a change to fit the way maintainer feels is the best for the project. When you decide to create some design changes, it is recommended to first discuss idea on [Pinta mailing list][11]. Try to get feedback from maintainer as soon as applicable. So small changes, several commits, discussion with maintainer and make some more changes.

#### Fixing a Bug

If you plan to work on a bug that has been registered on our [Launchpad page][1], then go to the relevant bug and make sure no one else is already working on it, then leave a comment saying that you are working on it.

#### Creating a Pinta Fork

First you need to make yourself an account with GitHub if you haven't already got one. It is recommended that you use your full name, because we need something to put in the credits! Then you fork the [PintaProject Repository][5], and pull the code down to your local machine. (All explained [here][6].)

#### Writing, Compiling and Testing

This is where the magic happens! Make whatever changes are necessary to the source code, but please do not attempt to clean up existing code. We are only interested in seeing functional changes to the code, if they are mixed with cosmetic changes it becomes very difficult to see what has actually changed. Build your code according to the [building instructions][7], and test it to make sure it does what it's supposed to and doesn't do anything it's not supposed to.

#### Committing your Fix

When you are satisfied that you have a great fix to share with the world, commit it to your GitHub fork. (See the second part of [Create A Repo][8].) Make sure that the commit message includes the bug number and a short description, this is vital so that the developers know what exactly they are looking at. Then it will be publicly visible for scrutiny, which comes in handy for the next step.

#### Sending a GitHub Pull Request

Pull requests are thoroughly explained [here][9]. You will want to send a pull request to the Pinta repository from your fork. When the developers see your request, they will test your solution and if it is good they will merge it into the Pinta source code. They will then close the bug on Launchpad and add your name to the credits as a contributor, and you get a lovely warm feeling inside from helping make the world a better place!

[1]: https://bugs.launchpad.net/pinta/+bugs
[2]: http://pinta.uservoice.com
[3]: https://translations.launchpad.net/pinta
[4]: http://progit.org/book/
[5]: https://github.com/PintaProject/Pinta
[6]: http://help.github.com/fork-a-repo/
[7]: https://github.com/PintaProject/Pinta/blob/master/readme.md
[8]: http://help.github.com/create-a-repo/
[9]: http://help.github.com/send-pull-requests/
[10]: https://bugs.launchpad.net/pinta/?field.searchtext=&orderby=-date_last_updated&search=Search&field.status%3Alist=NEW&field.status%3Alist=CONFIRMED&field.status%3Alist=TRIAGED&field.status%3Alist=INPROGRESS&field.status%3Alist=INCOMPLETE_WITH_RESPONSE&field.status%3Alist=INCOMPLETE_WITHOUT_RESPONSE&assignee_option=any&field.assignee=&field.bug_reporter=&field.bug_commenter=&field.subscriber=&field.structural_subscriber=&field.tag=easy-to-fix+&field.tags_combinator=ANY&field.has_cve.used=&field.omit_dupes.used=&field.omit_dupes=on&field.affects_me.used=&field.has_patch.used=&field.has_branches.used=&field.has_branches=on&field.has_no_branches.used=&field.has_no_branches=on&field.has_blueprints.used=&field.has_blueprints=on&field.has_no_blueprints.used=&field.has_no_blueprints=on
[11]: https://groups.google.com/forum/?hl=en#!forum/pinta