# MY README

### 2020-11-04

Nothing to see here...just wanted to see Simon's code. Unfortunately his tool doesn't import from the Twitter data export optimally. For example:

https://github.com/dannguyen/twitter-to-sqlite#importing-data-from-your-twitter-archive

```sh
$ twitter-to-sqlite import mydata.sqlite  mine_zipcontents/tweet.js
```

Will result in a `archive_tweet` table with just two fields, `id` (of table row) and `tweet` as a full JSON.

Probably easier to write my own tool?

