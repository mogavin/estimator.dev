# [EStimator](https://estimator.dev)

Calculate the size and performance improvement a site could achieve by switching to modern JavaScript syntax.

### Privacy

Submitting a URL for analysis is stateless. The service does not store any information about you or the URLs you analyze.
A minimal Google Analytics ping is used to record page visits _(URL and referrer)_ and JavaScript errors, as well as the total calculated size difference number _(but not the URL you entered)_.

### Hacking

```sh
# clone it
git clone git@github.com:GoogleChromeLabs/estimator.dev.git
cd estimator.dev

# install dependencies and firebase CLI
npm install
npm install -g firebase-tools

# start the server and functions
firebase emulators:start
```
