## What is this?

An example app in Polymer using `core-elements` (including `core-ajax`) and `paper-elements` to build a super simple interface for viewing the Polymer project's latest GitHub issues.

## How to Run

1. npm install
2. bower install
3. grunt server

## Important Note

We hit the GitHub API without authentication... GitHub is cool with this, but they throttle requests at 60 / hour from any IP address.

If you want to reload over and over again, you'll have to update the `core-ajax` calls in `elements/issue-list.html` and `elements/issue-comments.html`, adding your own auth keys.