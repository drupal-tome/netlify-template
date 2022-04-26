[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/drupal-tome/netlify-template)

# Netlify template for Tome projects

This project is a great place to start for building new Tome projects on Netlify.

To get started, click the "Deploy to netlify" button above and deploy a copy of
this template to Netlify.

# Requirements

- PHP 7+
- [Composer](https://getcomposer.org/)
- [Drush](https://github.com/drush-ops/drush-launcher#installation---phar)
- SQLite 3.6+ and the related PHP extensions

# Local usage

To install Tome locally, run:

```bash
drush tome:install
```

To start a local webserver, run:

```
drush runserver
```

then in another tab run:

```
drush uli -l 127.0.0.1:8888
```

and click the link to start editing content!

If you want to preview your static build locally, run:

```bash
drush tome:static
drush tome:preview
```

# Changing the install profile

By default this template uses [Bookish](https://github.com/drupal-tome/bookish),
an install profile built for Tome blogs. If you want to build a Drupal site from
scratch instead, you can run:

```
drush tome:init
```

And choose a different install profile from there.

# Further help

After logging in, click "Help" in the toolbar. Bookish has extensive
documentation located inside Drupal using the Help Topics module. A good place
to start would be the "Configuring your Bookish site" page, which will guide
you through personalizing the configuration of your site.
