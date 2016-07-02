# Browsertime

Access the Web Performance Timeline, from your browser, in your terminal!

Browsertime allows you to:
 1. Query timing data directly from the browser, to access [Navigation Timing](http://kaaes.github.io/timing/info.html), [User Timing](http://www.html5rocks.com/en/tutorials/webperformance/usertiming/),
[Resource Timing](http://www.w3.org/TR/resource-timing/), first paint and [RUM Speed Index](https://github.com/WPO-Foundation/RUM-SpeedIndex).
 1. Generate [HAR](http://www.softwareishard.com/blog/har-12-spec/) files (using [HAR Export trigger] (https://github.com/firebug/har-export-trigger) for Firefox and parsing the Chrome log for Chrome).
 1. Run custom Javascript scripts in the browser and get statistics for each run.

The 1.0 branch is to a large degree a re-write of the internal implementation, the cli interface, and the node API. It's
based on learnings from the previous releases of Browsertime, and their use in Sitespeed.io. It's still lacking features
from the 0.x releases, and the API is not final. However it should be a better foundation for future development, using
more modern Javascript features and a much more extensive test suite.

If you run into any issues getting started using Browsertime visit our [Issues Page](docs/issues.md) for some common issues and solutions.
