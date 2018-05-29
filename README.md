
# Super Twisted Trivia 
mIRC game for IRCWX Servers.

`/var/log/gitlab/postgresql/current`:

```
  1885  2014-08-08_16:28:43.71000 FATAL:  could not create shared memory segment: Cannot allocate memory
  1886  2014-08-08_16:28:43.71002 DETAIL:  Failed system call was shmget(key=5432001, size=1126563840, 03600).
  1887  2014-08-08_16:28:43.71003 HINT:  This error usually means that PostgreSQL's request for a shared memory segment exceeded available memory or swap space, or exceeded your kernel's SHMALL parameter.  You can either reduce the request size or reconfigure the kernel with larger SHMALL.  To reduce the request size (currently 1126563840 bytes), reduce PostgreSQL's shared memory usage, perhaps by reducing shared_buffers or max_connections.
  1888  2014-08-08_16:28:43.71004       The PostgreSQL documentation contains more information about shared memory configuration.
```

[![NPM Version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Downloads Stats][npm-downloads]][npm-url]

![RedXProjects](https://scontent-ams3-1.xx.fbcdn.net/v/t1.0-9/22228533_1157881041010833_2284566100979801844_n.png?_nc_cat=0&oh=ce7eb160aa17894e8e5b6f60eaf7ad8d&oe=5B89474D) 

## Update Patch Notes & Hotfixes

* 2.0.1
    * Next Update release: may 30 2018
```
`2.0.1 Trivia Notes:`;
* FIXED: Huge trivia error, Points doubler questions.
* The error occurs when there are more players that answer correct within the question time.
* The second player gets 1.5 times the points instead of 0.5.
* The third gets 1.33 times the points instead of 0.33 etc

* UPGRADE: Theme and bug fix.
* Theme is upgraded and bugs are fixed.

* ADD: Donation jackpot
* 250 points is added in pot for every question that is answered correctly.

* ADD: happy hour.
* Happy hour will dubble points on questions and jackpot if answer is right.
* happy hour starts every 3 hours for 1 hour, To see timers typ: !happyhour

* ADD: More bonus.
* Everyone will now get bonus if rise in: CPM, Hof, Speed list.

* ADD: Left or Right
* Left or Right is a mini game that can popup randomly
* You need to make a choice !left Or !right, bot will make a randomly choice what side will win.

* ADD: Daily reward system
* Daily bonus everyday on joining the room
* When joining the room you will get 5 daily reward tickets
* To use the tickets typ !daily
* Things you can win in daily: Trivia points 90%, Lucky-Tickets 40%, Silver-hammer: 20%, Brown-hammer: 10%.
```
* 1.1.1
    * ADD: Bonus games (Frenzy and Roa)
    * Change: User Commands `@trivia` to `>help` 
* 1.1.0
    * New Layout and updated emoticons
    * CHANGE: sets of `foo(tokens)` to `bar(tokens)`
* 1.0.1
    * Work in progress


## Tips, Tricks and commands.

Describe how to install all development dependencies and how to run an automated test-suite of some kind. Potentially do this for multiple platforms.

```sh
Coming soon
```

## Team Project Twisted Trivia
<a name="team-members"></a>Team Members

"Reddix" Talk@redxprojects.com

"Luc" Talk@redxprojects.com

"Eniam Reg" Talk@redxprojects.com

"Danger" Talk@redxprojects.com


## Information

RedXProjects – [@RedXProjects](https://www.facebook.com/RedXProjects/) – Talk@redxprojects.com

Under the GNU license. See ``LICENSE`` for more information.

Future version will be free to download.

[https://github.com/Red-X-Projects/Trivia](https://github.com/Red-X-Projects/Trivia)

## Contact

[website]: https://redxprojects.com
[facebook]: https://www.facebook.com/RedXProjects/
[email]: Talk@redxprojects.com
[other projects] : https://github.com/Red-X-Projects

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki

