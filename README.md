# clj-adn

A really simple wrapper for ADN. It really can't do much yet, but I'll be working on it throughout the summer.

## Config

in src/clj_adn/config.clj, be sure to set your token, available from [Dev-Lite](http://dev-lite.jonathonduerig.com/)

## Usage

Currently, you may create a new post, follow a user, unfollow a user, and retrieve information regarding a user (including yourself). Many more features are planned, so stay tuned!

```clojure
(follow "@SirSkidmore")
(retrieve-user "@SirSkidmore")
(post "Hello from a Clojure REPL!")
```
### Disclaimer

I'm not going to pretend this code is great, so don't expect really great things. It'll be a great work in progress, and I really hope it turns out well throughout my summer break.

If you have any questions, feel free to DM or mention me over on ADN at [@SirSkidmore](https://alpha.app.net/sirskidmore).

### TODOs
* [] Write some docs
* [] Add in rest of post endpoints
* [] beautify json output of endpoint calls

## License

Copyright © 2013 Taylor Skidmore

Distributed under the Eclipse Public License, the same as Clojure.
