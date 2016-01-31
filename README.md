gumtree-watcher
===============

The refresh button hurts my finger. So I automated that.

Check the latest items from gumtree.com.au and send a message through Telegram.

Requirements
------------

- [Telegram API](https://core.telegram.org/api) (user or bot token)
- NodeJS obviously

Getting Started
---------------

    $ git clone https://github.com/haruair/gumtree-watcher.git
    $ cd gumtree-watcher
    $ npm install # do the right thing
    $ cp config.sample.json config.json
    $ vi config.json # Edit the config
    $ node index.js # May you can do via cron
