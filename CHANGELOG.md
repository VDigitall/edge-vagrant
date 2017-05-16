# Change log:

## [1.0.0dev6] - 2017-05-16 (not released)
### Added Vagrant:
- Update dist to fedora/25-cloud-base
### Added EDGE:
- Implemented monitoring as option
- Replaced monitoring metrics storage Couchdb to StatsD
- Fix minor bugs
### Added MONITORING:
- Update Netdata
- Replaced python plugins for NetData to statsd apps configs

## [1.0.0dev5] - 2017-03-23
### Added EDGE:
- Slow clients sifted out
### Added MONITORING:
- Edge delay from the CDB displayed
- Requests' duration to the CDB displayed
- Number of elements received from the CDB in queue displayed
- Time of the last request to the CDB recorded
- Number of elements received in the last request to the CDB displayed
