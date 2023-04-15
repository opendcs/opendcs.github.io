Development Practices
#####################

General Development
-------------------

This is no formal procedure for developing features and bugfixes for opendcs.
If you are going to perform work please create feature requests and bug reports should be done through the github issues page:
https://github.com/opendcs/opendcs/issues so that everyone knows what's going on and can chime in and not duplicate work.

At this time most work is done by contractors under contract; some volunteer development work is done.
Work will be done on and relevance to existing issues or best effort.

Pull requests are most welcome, smaller changes will be reviewed faster. Do not open PR with large changes before consulting
with the team.

Releases
--------

Releases will be made no more than monthly. *Except* in cases of security fixes that justify sooner releases.

Releases will consist of the most recent fixes and feature implementations merged into the default (or version) branch.

The process will be as follows:

- Work is performed and merged into the default (or version) branch
- at the middle of the month a vote is taken
  - if passed release, is done then
  - if fails, work continues until satisfied OR it's the end of the month and there are no 
    show stopper bugs.
    - If there are egregious show stoppers there will be no release for the month.

Show stopper bugs are things that prevent the components from working at all or causing problems. Missing features,
 while certainly annoying for the requestor thereof, shall not prevent a release.

NOTE: The OpenDCS team will not promise a feature by a version number. The OpenDCS team will not stress themselves out to 
fulfill someone elses promise thereof. However, we will always work to help make the software better.
