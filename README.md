# Sermonindex.net (API)

What is this all about
> This is a very basic static API set of json files, that will give you access to all of the sermons from sermonindex

## How Does it Work?

Get an index of any of the areas with the `_sermonindex.json` file in that peticular folder as it will serve as a quick guide to access all the content of that area. Once you have that index, you can access any of the sermon bundles to finaly get all the sermon data.

### Getting the sermon index

> get the speakers listing
```
// github
https://raw.githubusercontent.com/sermonindex/api/master/speaker/_sermonindex.json
// sermonindex
http://www.sermonindex.net/api/speaker/_sermonindex.json
// your own clone
http://www.yourowndomain.com/api/speaker/_sermonindex.json
```

> get the scripture listing
```
// github
https://raw.githubusercontent.com/sermonindex/api/master/scripture/_sermonindex.json
// sermonindex
http://www.sermonindex.net/api/scripture/_sermonindex.json
// your own clone
http://www.yourowndomain.com/api/scripture/_sermonindex.json
```

> get the scripture listing of one book
```
// github
https://raw.githubusercontent.com/sermonindex/api/master/scripture/john/_sermonindex.json
// sermonindex
http://www.sermonindex.net/api/scripture/john/_sermonindex.json
// your own clone
http://www.yourowndomain.com/api/scripture/john/_sermonindex.json
```

> get the topical listing
```
// github
https://raw.githubusercontent.com/sermonindex/api/master/topic/_sermonindex.json
// sermonindex
http://www.sermonindex.net/api/topic/_sermonindex.json
// your own clone
http://www.yourowndomain.com/api/topic/_sermonindex.json
```

The returned json index will give you a paths to the sermons, you will need to prepend the URL that you would like to use, for example:

With this path `speaker/leonard_ravenhill.json`

> if you are using gitHub
```
https://raw.githubusercontent.com/sermonindex/api/master/speaker/leonard_ravenhill.json
```

> sermonindex
```
http://www.sermonindex.net/api/speaker/leonard_ravenhill.json
```

> your own domain (clone)
```
http://www.yourowndomain.com/api/speaker/leonard_ravenhill.json
```

### how to clone this repository to your own server

```
$ git clone https://github.com/sermonindex/api.git
```

## more information to follow
