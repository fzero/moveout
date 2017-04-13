# It's time to move out! - Getting your data out of the US

These are the speaker notes / outline for the presentation. The deck was created with [Reveal.js](http://lab.hakim.se/reveal-js) and can be found in the [`/deck`](deck) folder.

## Who am I?

* Fabio Neves
* Brazilian by accident, Canadian by choice
* Infant nerd, professional developer since 1997
* Instructor at Lighthouse Labs and freelance developer
* Not exactly a tinfoil hat guy

## Why?

* First of all: the cloud is nothing more than someone else's computer
  * Yes, this includes everything Google, Facebook, Instagram, Microsoft...
* The location of those computers matter
* Who controls those computers matters even more
* Most of the cloud is hosted in the US
* The US government gave themselves (unilaterally!) the right to spy on everyone else!
* Have you read the news lately?

## What you can do?

* You don't need to abandon the cloud entirely, but you can keep your stuff in a safer place!
* Should you trust a single entity with your data? Google stores all your email, contacts, calendar, location history...
* Using your data - even if slightly anonymized - is their business.
* How much can they guess about you just by looking at metadata?

## Email

* Gmail isn't the only game in town
* It's relatively safe and has good encryption when passing messages around...
* ...but it's a huge target for NSA and hackers in general.
* The same is valid for all large email providers.

### Alternatives

* Protonmail
  * End-to-end encrypted email. They don't have a way to read messages stored in their servers!
  * Hosted in Switzerland
  * Good free tier
  * Downside: doesn't offer IMAP or POP3 access.
* Manual PGP encryption
  * Requires a lot of work
  * Keybase.io makes it a bit less hard (still not easy)

## Storage

* Dropbox isn't very safe
  * Condoleezza Rice is on their board of directors
  * Yes, that lady from the Bush administration
  * Nothing is encrypted
  * There has been leaks
* Google Drive is a bit better, but all restrictions mentioned before apply

### Alternatives

* Sync.com
  * End-to-end encrypted
  * Canadian!
  * Very good pricing
  * Downsides: doesn't have document editing features like Dropbox and Google Docs
  * Doesn't have a native Linux client (there are workarounds though)
* owncloud.org
  * Use one of many providers located in several places around the world
  * You can install it on a RaspberryPi and have the most personal cloud computing platform ever! (https://pimylifeup.com/raspberry-pi-owncloud/)

## Social media

* That's a tough one!
* You're pretty much paying for the services with your data and privacy
* BUT! There have been some interesting recent developments...

### Mastodon

* Decenralized, open-source, ad-free social network
* It's gaining traction
* Anyone can host a server
* Servers talk to each other, so it's at one time more resilient, diverse and interesting than Twitter and Facebook put together

## Slack

* Slack is a step backwards
  * Proprietary and closed re-implementation of IRC, which is open-source and distributed
  * There are IRC clients based on IRC v3 that have pretty much the same features
  * Yes, there are very good web interfaces

### Alternatives

* IRC!
* Riot.im
  * Looks more like Slack
  * Decentralized, modern architecture based on the Matrix protocol
  * Yes, you can host your own

## Code

* Github and Bitbucket are not bad
* Open-source projects are public anyway
* Things might not be so clear-cut for private projects though

### Alternative

* Gitlab
  * Host your own GitHub!
  * Very easy to install and maintain
  * Excellent for closed, company-specific projects

## Hosting

Here you need to make a decision:

Is it enough for you and your users to have the data **situated** out of the US while **still under control** of a US company or do you want to **actually be completely out of US jurisdiction**?

The first case is easier. Amazon, DigitalOcean, Linode and others have datacenters in several different locations.

The second case is ok if you can do your own operations, but there's currently no substitute for automated cloud hosting services like Heroku, Cloud9 or Google App Engine.

### Alternatives

* 1984hosting.com
  * Based in Iceland
  * Famous for their stance on privacy and civil rights
* OVH
  * French company
  * Offers decently-priced VPS
  * Has datacenters all over the world (including Canada)

## Notice a common theme?

* Decentralization!
* The internet was invented to be decentralized
* It **was** very decentralized in the beginning
* Facebook, Amazon and Google changed that
* Make no mistake **this is NOT a good thing!**
* You **can** and **should** take back control of the web!
