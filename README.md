# Deploy to tilde.club

This is a GitHub action that deploys the `main` branch of any repo to your tilde.club `/~public_html` folder.

To use it:

* Copy the contents of `deploy.yml` to `.github/workflows/deploy.yml` in the repo you want to deploy
* Change the line `User username` to match your tilde.club username (e.g. `User ruben`)
* Create a new secret for your repo called `SSH_KEY` that contains the private key you use to log in to tilde.club
* ...
* Profit!
