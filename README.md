# Steem Binaries [![Build Status](https://travis-ci.org/mahnunchik/steem.svg?branch=master)](https://travis-ci.org/mahnunchik/steem) [![Run Status](https://api.shippable.com/projects/57ab51d9f0111a1000ef69ff/badge?branch=master)](https://app.shippable.com/projects/57ab51d9f0111a1000ef69ff)

[Steemit](https://steemit.com/) is a social media platform where everyone gets paid for creating and curating content. It leverages a robust digital points system, called Steem, that supports real value for digital rewards through market price discovery and liquidity.

## Binaries

This repository contains build script to produce binaries of `steemd` program for the following platforms:

* Mac OS
* Linux

All files are automatically compiled from [sources](https://github.com/steemit/steem) and uploaded to the [releases page](https://github.com/mahnunchik/steem/releases).

Build environments:

* Mac OS CI - [travis](https://travis-ci.org/mahnunchik/steem)
* Linux CI - [shippable](https://app.shippable.com/projects/57ab51d9f0111a1000ef69ff/status/)

## How to Mine

1. Download and extract binaries from https://github.com/mahnunchik/steem/releases
2. Collect your `ACTIVE` private key (for example from https://steemit.com/@accountname/permissions page, replace `accountname` with yours)
3. Mine!
```bash
$ ./steemd --miner=["accountname","ACTIVE_PRIVATE_KEY"] --witness="accountname" --seed-node="52.38.66.234:2001"
```

Config clarification can be found here: https://github.com/steemit/steem/issues/245

## More info

* [Steem](https://github.com/steemit/steem)
* [Steemit](https://steemit.com/)
