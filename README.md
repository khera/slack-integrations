slack-integrations
==================

Scripts to integrate with the slack.com group messaging service.

slack-nagios-notify
-------------------

Posts a notice from Nagios into a Slack channel using the *Incoming
Webhooks* integration, which will need to be enabled in Slack.

Written in Perl. Requires the modules HTTP::Request::Common,
LWP::UserAgent, and JSON.


slack-subversion
----------------

Posts the commit message from Subversion to the Slack integration for
subversion. The channel that the notice goes to is specified in the
integration on the Slack web site, so there may be multiple
integrations defined for different repos.

Written in Perl. Requires the modules HTTP::Request::Common,
LWP::UserAgent, JSON, Getopt::Long, and File::Which.
