![DeSo Logo](src/assets/deso/camelcase_logo.svg)

# About BitFlare

[![Deploy on Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/desodev/BitFlare)

BitFlare is an easy frontend for BitClout that you can host on CloudFlare Pages.

* Click to Deploy
* No need to install the Node backend
* No waiting around for 24 hour sync of Blockchain

# Support

This was created by [@tijn](https://bitclout.com/u/tijn).

# Limitations

Please be aware the following limitations exist:

* You dont have access to the admin tab
* Netlify just hosts the frontend
* The backend (eg bitclout api) uses a a cluster hosted `@tijn`
* The cluster has 2 nodes to make sure its up
* `@tijn` is only admin
  * only one to see admin tab
  * only one that can whitelist, verify, pin, or promote to global
* The global feed is relatively empty
* The 2 backend servers do not sync offchain data - eg whitelists, verified, etc

# About DeSo
DeSo is a blockchain built from the ground up to support a fully-featured
social network. Its architecture is similar to Bitcoin, only it supports complex
social network data like profiles, posts, follows, creator coin transactions, and
more.

[Read about the vision](https://docs.deso.org/#the-ultimate-vision)

# About This Repo
Documentation for this repo lives on docs.deso.org. Specifically, the following
docs should give you everything you need to get started:
* [DeSo Code Walkthrough](https://docs.deso.org/code/walkthrough)
* [Setting Up Your Dev Environment](https://docs.deso.org/code/dev-setup)
* [Making Your First Changes](https://docs.deso.org/code/making-your-first-changes)
