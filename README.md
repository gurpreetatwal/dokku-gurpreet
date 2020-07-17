# dokku-gurpreet

Custom dokku plugin for my personal installations of dokku.

## Requirements

- dokku 0.21.x+

## Installation

```shell
sudo dokku plugin:install https://github.com/gurpreetatwal/dokku-gurpreet gurpreet
```

## Commands

None at the moment.

## Triggers

###### [`nginx-dokku-template-source`](http://dokku.viewdocs.io/dokku/development/plugin-triggers/#nginx-dokku-template-source)

Replaces the [default dokku nginx config](https://github.com/dokku/dokku/blob/master/plugins/nginx-vhosts/templates/dokku.conf.sigil) with a barebones config which only serves to include the application-specific configs. The default dokku nginx config contains SSL settings which are already specified in my [nginx config](https://github.com/gurpreetatwal/nginx.conf)
