---
layout: default
title:  "Product Ship Sequence"
---
## 0. Once All Stories Required for Release Milestone In Pivotal Are Complete

Review and verify that features are aligned to validate the Initial Release Hypothesis.

Confirm how initial release cohorts will be designated and tracked

### Pre-Release Checklist

* Application Security Audit
* Verify Setup of Monitoring Tools:
  * Airbrake
  * New Relic
  * If heroku:
     * are we running a [production database](https://devcenter.heroku.com/articles/upgrade-heroku-postgres-with-pgbackups#provision-new-plan)?
     * do we have a [custom maintenance page](https://devcenter.heroku.com/articles/maintenance-mode)? (or a story to make one)
  * Are the admin emails going to multiple team members or blazing cloud folks who can alert the team?
* Review analytics tools and what data points will be used to validate success
  * Flurry
  * Google Analytics

## 1. Ship Decision

* What is the process?
* Who is involved?
* Current Ship Status

## 2. App is Approved and Released In iTunes within 24 Hours

* Submit 1.x release

## 3. Not Stop Ship Work Items

### Escalation Plan
* New Relic notifications setup for client
* Airbrake notifications setup for client
* Heroku notifications for client

### Marketing Plan/Social Campaign (start executing after N days)
* Blog posts + social media from official client blog/fb/twitter
* Blazing Cloud also markets the app:
* As individuals from our own blogs/twitter/etc, and get our friends to "like" the FB and follow them on Twitter
* As Blazing Cloud from the official BzC blog

## iOS App Submission Process
* Review (https://github.com/blazingcloud/blog.blazingcloud.net/wiki/iOs-App-Submission-Process)
