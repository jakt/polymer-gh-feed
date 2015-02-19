## How to Run

1. npm install
2. bower install
3. grunt server

## Important Note

By default, this little app hits the GitHub API without authentication. GitHub is cool with this but throttles requests at 60 / hour from any IP address.

So, if you want to load this thing over and over again, you'll have to update the `core-ajax` calls in `elements/issue-list.html` and `elements/issue-comments.html`, adding your own auth keys.