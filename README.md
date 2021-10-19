# Drupal 8.x Project Development Checklist
A checklist of common tools, settings, modules etc to check for a Drupal 8.x web project

> Want to use a **Docker** image for development? Head to https://github.com/theodorosploumis/gitpod-drupal-workspace!

**How to use this?**
I usually copy this checklist to a Github issue so I won't forget anything. 
Most of the times I delete items from the list so this is the full list.

 - [Get raw README.md](https://raw.githubusercontent.com/theodorosploumis/drupal8-checklist/master/README.md)
 - [Edit README.md](https://github.com/theodorosploumis/drupal8-checklist/edit/master/README.md)

## Server type

 - [ ] Debian 64.x, stable (Xenial 16.04)


## Server setup

Prefer to install all software globally.

 - [ ] php7 (see [required php extensions](https://drupal.org/docs/8/system-requirements/php-requirements) for drupal 8.x)
 - [ ] mysql
 - [ ] apache2/nginx
 - [ ] git
 - [ ] patch
 - [ ] [drush](http://docs.drush.org/en/master/install/#installupgrade-a-global-drush)
 - [ ] [drupal console](https://hechoendrupal.gitbooks.io/drupal-console/content/en/getting/installer.html)
 - [ ] [composer](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx)
 - [ ] openssh-server
 - [ ] nodejs/npm (if needed)

## Dev Packages (if needed)

 - [ ] [sass-lang.com](https://sass-lang.com/)

## SaaS

 - [ ] Create Github/Bitbucket repository
 - [ ] Create Project Management project (eg [TeamWork](https://teamwork.com))
 - [ ] Create a Trello board (if using Trello)
 - [ ] Setup Slack
 - [ ] Setup CI (eg Travis)

## Modules

 - [ ] [admin_toolbar](https://www.drupal.org/project/admin_toolbar)
 - [ ] [ctools](https://www.drupal.org/project/ctools)
 - [ ] [pathauto](https://www.drupal.org/project/pathauto)
 - [ ] [pathologic](https://www.drupal.org/project/pathologic)
 - [ ] [redirect](https://www.drupal.org/project/redirect)
 - [ ] [token](https://www.drupal.org/project/token)
 - [ ] [google_analytics](https://www.drupal.org/project/google_analytics)
 - [ ] [simple_sitemap](https://www.drupal.org/project/simple_sitemap)

---

 - [ ] [backup_migrate](https://www.drupal.org/project/backup_migrate)
 - [ ] [config_update](https://www.drupal.org/project/config_update)
 - [ ] [config_devel](https://drupal.org/project/config_devel)
 - [ ] [devel](https://www.drupal.org/project/devel)
 - [ ] [features](https://www.drupal.org/project/features)
 - [ ] [masquerade](https://www.drupal.org/project/masquerade)
 - [ ] [stage_file_proxy](https://www.drupal.org/project/stage_file_proxy)

## Themes (base)

 - [ ] [omega](https://www.drupal.org/project/omega)
 - [ ] [bootstrap](https://www.drupal.org/project/bootstrap)
 - [ ] [zurb_foundation](https://www.drupal.org/project/zurb_foundation)
 - [ ] [kashmir](https://drupal.org/project/kashmir)
 - [ ] [neato](https://www.drupal.org/project/neato)
 - [ ] [basic](https://www.drupal.org/project/basic)
 - [ ] [xtheme](https://www.drupal.org/project/xtheme)
 - [ ] [gesso](https://www.drupal.org/project/gesso)
 - [ ] [radix](https://www.drupal.org/project/radix)
 - [ ] [cog](https://www.drupal.org/project/cog)
 - [ ] [bear_skin](https://www.drupal.org/project/bear_skin)
 - [ ] classy (core theme)
 
---

 - [ ] [adminimal_theme](https://www.drupal.org/project/adminimal_theme)

## Drupal Settings

 - [ ] Enable dev mode
 - [ ] Enable php error_log
 - [ ] Enable apache2 error_log
 - [ ] Copy ssh keys

## Site Architecture

 - [ ] Content types
 - [ ] Vocabularies
 - [ ] Entity Fields
 - [ ] Blocks
 - [ ] Menus and menu links
 - [ ] View modes
 - [ ] User Roles
 - [ ] Views
 - [ ] Text editor filters
 - [ ] Text editor widgets/plugins
 - [ ] Image styles
 - [ ] REST pages
 - [ ] Site functionality (eg search, mailchimp etc)
 - [ ] New things to try (eg a new tool)

## Testing

 - [ ] User Scenarios/Stories
 - [ ] Test UI functionality (behat)
 - [ ] Test user permissions (PhpUnit)
 - [ ] Test user input (behat)
 - [ ] Test browsers (browserstack etc)
 - [ ] Test devices (mobile, tablet, desktop)
 - [ ] [W3C WAI level 1 accessibility validation](https://validator.w3.org/)
 - [ ] [Google Mobile Friendly](https://www.google.com/webmasters/tools/mobile-friendly/) test
 - [ ] [Google PageSpeed](https://developers.google.com/speed/pagespeed/insights/) test
 - [ ] [Pingdom Website Speed Test](http://tools.pingdom.com/fpt/)
 - [ ] [Yellow Lab Tools](https://yellowlab.tools)

## Development tasks

 - [ ] Create Project folder
 - [ ] Create drush aliases
 - [ ] git-flow init
 - [ ] drupal console chain commands
 - [ ] Setup **cron jobs**
 - [ ] Set xdebug
 - [ ] IDE setup (eg Phpstorm)
 - [ ] Create [teamocil](www.teamocil.com) file
 - [ ] Create bash aliases

## After development tasks

 - [ ] Disable modules: *_ui, dblog, devel, admin_menu, simplytest, kint.
 - [ ] Enable Caches
 - [ ] Enable syslog module
 - [ ] Provide customer credentials
 - [ ] Maintenance aggreement
 - [ ] Submit to SE (eg Google), use xmlsitemap
 - [ ] Submit to [Google Analytics](https://analytics.google.com)
 - [ ] Submit to [Google Webmaster tools](https://www.google.com/webmasters/tools)
 - [ ] Submit to Showcase sites
 - [ ] Publish on my personal site (work)
 - [ ] Publish any Open source project that can be useful
 
