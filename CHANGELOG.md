# Changelog

## 0.3.0

* [ADDED] Auto re-subscription
* [ADDED] Exceptions are raised via an event and aren't thrown (unless there are no event handlers)
* [ADDED] Auto-reconnections now backs off by 1 second increments to a maximum of a retry every 10 seconds.
* [ADDED] The WebSocket Host can be configured
* [ADDED] You can now subscribe prior to connecting
* [REMOVED] `Pusher.Send` method on the public API
* [CHANGED] Update dependencies
  * Newtonsoft.Json 7.0.1
  * WebSocket4Net 0.13.1

### 0.2.0

* [CHANGED] Update package dependencies
  * Newtonsoft.Json 6.0.4
  * WebSocket4Net 0.10