<img src="https://raw.githubusercontent.com/sermonindex/audio_api/master/api-image.jpg">

# Sermonindex.net (Audio API)

What is this all about
> This is a very basic static API set of json files, that will give you access to all of the sermons from sermonindex

## How Does it Work?

Get an index of any of the areas with the `_sermonindex.json` file in that peticular folder as it will serve as a quick guide to access all the content of that area. Once you have that index, you can access any of the sermon bundles to finaly get all the sermon data.

### Getting the sermon index

> get the speakers listing
```
// github
https://raw.githubusercontent.com/sermonindex/audio_api/master/speaker/_sermonindex.json
// sermonindex
http://api.sermonindex.net/audio/speaker/_sermonindex.json
// your own clone
http://www.yourowndomain.com/audio/speaker/_sermonindex.json
```

> get the scripture listing
```
// github
https://raw.githubusercontent.com/sermonindex/audio_api/master/scripture/_sermonindex.json
// sermonindex
http://api.sermonindex.net/audio/scripture/_sermonindex.json
// your own clone
http://www.yourowndomain.com/audio/scripture/_sermonindex.json
```

> get the scripture listing of one book
```
// github
https://raw.githubusercontent.com/sermonindex/audio_api/master/scripture/john/_sermonindex.json
// sermonindex
http://api.sermonindex.net/audio/scripture/john/_sermonindex.json
// your own clone
http://www.yourowndomain.com/audio/scripture/john/_sermonindex.json
```

> get the topical listing
```
// github
https://raw.githubusercontent.com/sermonindex/audio_api/master/topic/_sermonindex.json
// sermonindex
http://api.sermonindex.net/audio/topic/_sermonindex.json
// your own clone
http://www.yourowndomain.com/audio/topic/_sermonindex.json
```

The returned json index will give you a paths to the sermons, you will need to prepend the URL that you would like to use, for example:

With this path `speaker/leonard_ravenhill.json`

> if you are using gitHub
```
https://raw.githubusercontent.com/sermonindex/audio_api/master/speaker/leonard_ravenhill.json
```

> sermonindex
```
http://api.sermonindex.net/audio/speaker/leonard_ravenhill.json
```

> your own domain (clone)
```
http://www.yourowndomain.com/audio/speaker/leonard_ravenhill.json
```

## How to clone/use this repository on your own server/website

> we prefer you doing this as it spreads the load a little, to insure this project remains fast and stable.

So you open the root foulder of your website, and make sure you don't have any other folder called `audio` in it alread, if you do, then change the target folder in the clone command to a name like `audio_api` so to insure that it does not conflict with existing folders.

```
$ git clone https://github.com/sermonindex/audio_api.git audio
```
Remember to update the API atleast once a month, as we are also constantly working on improving the API, and so to insure that all your links work, run a `git pull origin master` inside the audio (target) folder. This will update the whole API with all the new changes and improvements.

> How to manually run an update (remember to set the path)
```
$ cd /home/path_to/public_html/audio/
$ git pull origin master
```

If you would like to automate these updates via a `cronjob`, [read this post](https://stackoverflow.com/a/4415927/1429677) for some guidance.

## [Support this project](http://www.sermonindex.net/give/)

With over 100 million sermons distributed in 10 years of ministry, SermonIndex has touched an countless amount of believers. Since the inception of SermonIndex we have sought as best as possible to not make specific needs known for the ministry. Our [trust is in God](http://www.sermonindex.net/give/) for what He desires this ministry to accomplish, till the coming of the Lord.

