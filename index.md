# Mail Tool

Mail Tool is a personal email automation utility. It sends email messages and
attachments through the Gmail API on behalf of the account owner.

## What Mail Tool does

- Sends user-composed messages, reports, notifications, and attachments.
- Uses OAuth authorization instead of storing a Gmail password.
- Supports unattended sending from a user-controlled server after initial
  authorization.

## Data access

Mail Tool requests only the Gmail scope:

https://www.googleapis.com/auth/gmail.send

This scope allows the app to send email as the authorized account. Mail Tool
does not request access to read the inbox, search messages, modify labels,
manage contacts, or delete mail.

## Data handling

OAuth credentials and refresh tokens are stored on the user-controlled system
with restricted file permissions. Message content and recipients are processed
only to deliver the requested email. Mail Tool does not sell, rent, or share
Google user data with advertisers or data brokers.

Read the full [Privacy Policy](privacy.html) and [Terms of Service](terms.html).

## Contact

Questions about Mail Tool or this website can be sent to
[zhen996688@gmail.com](mailto:zhen996688@gmail.com).

_Last updated: November 8, 2026_
