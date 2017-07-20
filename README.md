# \<cameron-social-media-timeline\>

This application is my own implementation of a social media timeline that will display pictures of uniform size, along with any associated text, date, user, and other data that may come with the post.

# My Thought Process

When completing this part of the technical challenge, I wanted to be able to
create a web application that was well organized and structurally sound on the
UI. I wanted my web application to be able to respond to the possibility of
varying browser sizes. I wanted the application to be able to display posts in
order from most recent to early. Lastly, I wanted the application to be able to
have a back up in the case that the API or whatever back end we are using fails.
In the case that my application does not have any images to show, there is an
alternative element that shows on the UI instead. 

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
