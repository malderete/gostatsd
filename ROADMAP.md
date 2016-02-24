Roadmap
-------

Pri 1
-----

* [x] Support `Set` metric
* [x] Improve `graphite` backend reliability by re-opening connection on each flush or implementing retry on error
* [x] Add `statsd` backend to allow load balancing the statsd server / running statsd server HA
* [x] Add `datadog` backend
* [x] Add more timers aggregations e.g. mean, standard deviation, etc.
* [ ] Add tests
* [ ] Add load testing
* [ ] Review reset of counters, gauges, timers, etc. using last flush time and an expiration window
* [x] Add support for global metrics namespace

Pri 2
-----

* [ ] Add `influxdb` backend
* [ ] Fix gomatelinter issues
* [ ] Implement stats by backend e.g. last flush, last flush error, etc.
* [ ] Support `Histogram` metric
* [ ] Support `Event` metric
* [ ] Fix value of metrics displayed in console
* [x] Fix value of metrics displayed in web UI
* [ ] Rate limiting per source ip address

Pri 3
-----

* [x] Improve web console UI look'n'feel
