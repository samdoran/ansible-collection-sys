Roles useful for managing system health and backups

## Roles ##

- `samdoran.sys.backups`
- `samdoran.sys.benchmark` - Run Linux benchmarks
- `samdoran.sys.borg`
- `samdoran.sys.entware` - Install [Entware][] on Synology DSM
- `samdoran.sys.scrutiny` - Install and configure the [Srutiny][] metrcs collector
- `samdoran.sys.uptime_kuma` - Configure [Uptime Kuma][]


## Playbooks ##

- `ansible-playbook samdoran.sys.geekbench` - Runs the Geekbench benchmark. Requires hosts in a `benchmark` group.


[Uptime Kuma]: https://github.com/louislam/uptime-kuma
[Entware]: https://github.com/Entware/Entware/wiki
[Scrutiny]: https://github.com/AnalogJ/scrutiny
