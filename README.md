ChatOps Demo Hubot and HipChat
==============================

Getting Started
---------------

Clone a repository.

```
$ git clone https://github.com/hansode/chatops-demo-hubot-hipchat.git
$ cd chatops-demo-hubot-hipchat
```

Create `~/.hubotrc`

```
$ vi ~/.hubotrc
```

```
export HUBOT_HIPCHAT_JID="********"
export HUBOT_HIPCHAT_PASSWORD="********"
export HUBOT_LOG_LEVEL="debug"
```

Run hubot.

```
$ ./bin/hubot-hipchat-jenkins
```

Contributing
------------

1. Fork it ( https://github.com/[my-github-username]/chatops-demo-hubot-hipchat/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

License
-------

[Beerware](http://en.wikipedia.org/wiki/Beerware) license.

If we meet some day, and you think this stuff is worth it, you can buy me a beer in return.
