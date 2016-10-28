# analytics.js-integration-anyhost [![Build Status][ci-badge]][ci-link]

Integration for [Analytics.js][] - Allow to send analytics data to any host.

Why not just sending pull requests to [analytics.js-integration-segmentio]:
* I want to allow to send analytics data to any host not only segment.io. Thought since [v3.1.1](https://github.com/segment-integrations/analytics.js-integration-segmentio/releases/tag/3.1.1) it is possible already (using the apiHost option) but the name still contains segmentio. Using a distinct and self-describing name is a better option.
* The duo packaging compatibility has been removed since v2.0.0 but we need that in order to build the current version of [Analytics.js] (v2.11).
* I would like to be as close to the other components as I could without big changes and backporting features after v2.0.0.

## License

Released under the [MIT license](License.md).


[Analytics.js]: https://segment.com/docs/libraries/analytics.js/
[ci-link]: https://circleci.com/gh/tomako/analytics.js-integration-anyhost
[ci-badge]: https://circleci.com/gh/tomako/analytics.js-integration-anyhost.svg?style=svg
[analytics.js-integration-segmentio]: https://github.com/segment-integrations/analytics.js-integration-segmentio
