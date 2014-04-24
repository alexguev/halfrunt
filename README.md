# halfrunt

A Clojure library designed to process data produced during the development of a software project with the goal of charting metrics to help developers and teams be more productive.

It is also the goal of this project to explore the use of:

- [docker](https://www.docker.io)
- [core.async](https://github.com/clojure/core.async)
- [datomic](http://docs.datomic.com)
- [memcached](http://memcached.org)
- [kafka](http://kafka.apache.org)
- [pedestal](https://github.com/pedestal)
- [om](https://github.com/swannodette/om)
- [react](http://facebook.github.io/react)


## Usage

FIXME

## TODO

- process build result data and store it in a format amenable to the generation of a chart to trend the number of failed builds per day.
  - store the data in datomic
  - expose end-point where data will be posted for processing
  - use: docker, datomic, core.async, pedestal


## License

Copyright © 2014 FIXME

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.
