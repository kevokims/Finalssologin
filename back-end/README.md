## Introduction

* Google -> https://console.developers.google.com/apis/dashboard
* Twitter -> https://developer.twitter.com/en/portal/dashboard
* Github -> https://github.com/settings/developers

## For Development:

* Switch to "Development" branch (git rebase -b Development)
* Fill out .env file with your secrets
* Make sure all auth providers are setup for http://localhost:4000
* Start ("yarn run dev")

## For Production:

* Switch to main branch (git rebase -b main)
* Fill out .env file with your secrets
* Make sure all auth providers are setup for your heroku app you made
