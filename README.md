
React Native Bank Account App
===

This example application is a test bed for deducing the best way to create a real-time, disconnected mobile cross platform app.
The notion of using a bank account as the example is simply because of common understanding. A bank account app can easily lend itself to
proving workflows for i.e. account authorisation and management, proving security particularly around the storage of secrets etc and realtime
particularly managing disconnected behaviour and requirements.

## Contents

:warning: **WORK IN PROGRESS** |
:star: **COMING SOON**

Not all of the below is yet fully implemented

### Application Blueprint

* 

### Testing Setup

* [Mocha](https://mochajs.org/) for unit testing application code
* [Enzyme](https://github.com/airbnb/enzyme) and fully mocked React Native for unit testing UI components
* [Istanbul](https://github.com/gotwarlost/istanbul) code coverage
* Utilities for end-to-end integration testing Redux state, including side effects and asynchronous actions

### Development & Deployment Infrastructure

* [Auth0](https://auth0.com/) for ready-to-use login and signup screens, user authentication and identity management
* [Bitrise.io](https://www.bitrise.io) configurations for Continuous Integration and beta app distribution
* :warning: [Google Tag Manager](https://www.google.com/analytics/tag-manager/) analytics
* :star: [Microsoft Code Push](http://microsoft.github.io/code-push) for Continuous Deployment and instant app updates


### Roadmap

* **TODO** Crash reporting
* **TODO** Android and iOS UI Testing with Calaba.sh?
* **TODO** Feature flags?
