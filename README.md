# Dokku
A free, self-hosted alternative to Heroku

### Where do I get Dokku

* [Dokku Website](http://dokku.viewdocs.io/dokku/)
* [Dokku Documentation](http://dokku.viewdocs.io/dokku/installation/)
* [Dokku Plugins](http://dokku.viewdocs.io/dokku/plugins/)
* [Dokku Clients](http://dokku.viewdocs.io/dokku/community/clients/)

> I recommend [`dokku-cli`](https://github.com/SebastianSzturo/dokku-cli) as a client since it runs similarly to Heroku Toolbelt.

> [Let's Encrypt](https://letsencrypt.org/), [PostgresSQL](http://www.postgresql.org/) and [New Relic](http://newrelic.com/) also have plugins that run with Dokku
> 
> * [`dokku-letsencrypt`](https://github.com/dokku/dokku-letsencrypt)
> * [`dokku-postgres`](https://github.com/dokku/dokku-postgres)
> * [`dokku-newrelic`](https://github.com/aegypius/dokku-newrelic)

### Easiest Deployment Ever

```bash
$ git push dokku master
```

### How do I get it?

Digital Ocean has a Dokku droplet that runs on Ubuntu 14.04 and uses Dokku 0.4.10

1. Go to Digital Ocean
> ![DO Homepage](http://imgur.com/rf6bTU8.jpg)


2. Create a new Droplet, and select the Dokku "One-Click-App"
> ![fiver](http://imgur.com/cLJLAwH.jpg)
> 
> ![App](http://imgur.com/VBhlXKZ.jpg)

3. Add your SSH keys
> ![SSH](http://imgur.com/vft5X23.jpg)

4. Now you have a droplet with an IP address
> ![Dash](http://imgur.com/C2DuO4k.jpg)
>
>![Droplet](http://imgur.com/G7YzcPO.jpg)

5. Run the deploy command
> ![Deploy](http://imgur.com/eapdaDd.jpg)
