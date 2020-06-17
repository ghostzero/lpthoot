# GhostZero's Twitch Toolkit

The main idea of this laravel package is to make it performant and easy to solve certain API problems with Twitch. Furthermore this package offers a toolkit to simplify certain processes (which have been provided by my [StreamKit](https://streamkit.gg/) platform):

* Twitch Webhook/Polling Management
* Twitch Webhooks as Laravel Events
* Twitch Username/ID Resolver & Cache
* Twitch Extension Guard Middleware

## Installation

```php
$schedule->command('twitch-toolkit:poll')->everyFiveMinutes();
$schedule->command('twitch-toolkit:subscribe-webhooks')->weekly();
```

## Webhooks

## Polling

```php
dispatch(new SubscribeTwitchWebhooks($channel));
```