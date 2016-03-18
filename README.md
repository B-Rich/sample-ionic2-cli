# Ionic2 CLI

### Info
- http://ionicframework.com/docs/v2/cli/
- https://forum.ionicframework.com/t/attention-upcoming-ionic-2-starter-changes/45058/23

### Downsides/questions
- why not a generator?
  - would be great to provide hooks for developers to automate setup of their ionic projects according to their own needs
- no `--no-open` :(
- integration
  - no out-of-the-box git integration
    - `www/`, `resources`, (when using sass) not in gitignore
  - ~~cumbersome sass integration - http://ionicframework.com/docs/cli/sass.html~~
  - no good integration with gulp/bower/yeoman
    - bower components not automatically added to index
    - new files / scss not automatically added to index
  - no \*lint integration
  - no testing integration
- obscured cordova version/integration
  - ~~source files in `www/`~~
  - build process?
  - https://github.com/driftyco/ionic-cli/blob/master/lib/ionic/cordova.js#L10
  - https://github.com/driftyco/ionic-app-lib/blob/master/package.json#L50
- no sub-generators
- file structure not compatible with
  - cordova?
  - components or google app recommendation?
