- [Network, Performance and Memory panel tips](#network-performance-and-memory-panel-tips)
  - [Monitoring requests](#monitoring-requests)
  - [Change loading behaviour](#change-loading-behaviour)
  - [Analyzing performance and memory reports](#analyzing-performance-and-memory-reports)

# Network, Performance and Memory panel tips

> The network and perfomance are tabs in the developer tools that help in monitoring the network requests and the performance of the application.

## Monitoring requests

  * You can see all the requests being made on the page when the dev tools is open.
  * Click Stop recording network log ![record-on](assets/record-on.png) on the Network panel. It turns grey to indicate that DevTools is no longer recording requests.
  * Click Clear ![clear](assets/clear-requests.png)  on the Network panel to clear all requests from the Requests table.
  * You can save requests across page loads, check the Preserve log checkbox on the Network panel. DevTools saves all requests until you disable Preserve log.
  * You can capture screenshots to analyze what users see as they wait for your page to load.
    To enable screenshots, click Capture screenshots Capture screenshots on the Network panel. It turns blue when enabled.
  * You can replay an XHR request, by right-clicking the request in the Requests table and select Replay XHR.
  * You can also filter throught the requests by selecting the filter and also sort through the requests by using the different options available.
  * You can see the response of a request by clicking on it to see the headers,preview respone and timing of the request.

## Change loading behaviour

  * To emulate how a first-time user experiences your site, check the Disable cache checkbox. DevTools disables the browser cache. This more accurately emulates a first-time user's experience, because requests are served from the browser cache on repeat visits
  * There's a new class of web apps, called Progressive Web Apps, which can function offline with the help of service workers. When you're building this type of app, it's useful to be able to quickly simulate a device that has no data connection.
    Check the Offline checkbox to simulate a completely offline network experience.
  * Emulate 2G, 3G, and other connection speeds from the Network Throttling menu.You can select from a variety of presets, such as Regular or Good 2G. You can also add your own custom presets by opening the Network Throttling menu and selecting Custom > Add.
    DevTools displays a warning icon next to the Network tab to remind you that throttling is enabled.

## Analyzing performance and memory reports

  * You can analyze performance and memory reports by recording the network performance. Use the performance and memory tabs respectively to analyze and optimize run time performance and memory usage.

  Listing down links which could help you in detailed understanding of the concepts
  - https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/
  - https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/reference#memory