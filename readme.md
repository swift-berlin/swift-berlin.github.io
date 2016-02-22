# swift.berlin

This is the repository to generate the website of [swift.berlin](http://swift.berlin).

Read [here](http://swift.berlin/how-to-become-a-speaker) how to become a speaker.

## Development

To serve the app on `localhost:3000` run

```bash
bundle
bundle exec jekyll serve
```

All talks are in the `_posts` folder with the following format:

```yaml
name: Jens Ravens
image: jensravens (referenced by name from img/speakers)
title: Taking Swift to the Server
company: nerdgeschoss
about: 'Jens is an iOS and OS X Developer, writing ObjC since 2006. Currently working at <a href="http://nerdgeschoss.de" target="new">nerdgeschoss</a> helping clients to create awesome apps.'
abstract: Swift on Linux is finally there. What about building your next big coding project in Swift instead of Rails or node.js?
links:
  -
    url: http://jensravens.com
    name: jensravens.com
  -
    url: https://twitter.com/jensravens
    name: '@JensRavens'
```
