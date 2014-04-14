### Goangular Auth Example

An example app using GoAngular to define routes with access permissions based on the connected GoInstant user.

### Setup

#### GoInstant

- Create an account at http://goinstant.com
- Enable `GitHub`, `Twitter`, `Facebook` authentication providers and set your Authorized Origins.
- Set your connect URL
 - in `server.js` replace `YOUR_CONNECT_URL` with your real connect URL

### Running Locally

#### Install

- `npm install`

### Run

- `npm start`
- `open http://localhost:5000`

### Heroku Deploy

- Install the [Heroku Toolbelt](https://toolbelt.heroku.com/)
- Create an app: `heroku apps:create <name>`
- Configure your connectUrl: `heroku config:set GOINSTANT_CONNECT_URL=https://goinstant.net/ACCOUNT/APP`
- Push to heroku: `git push heroku master`
