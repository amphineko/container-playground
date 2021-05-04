# system-telemetry

This deployment hosts a Influxdb-based telemetry database.

Telegraf agents that running in the cluster are responsible for fetching remote hosts (e.g SNMP agents and Redfish IPMIs).

There're also some Telegraf agents running outside the cluster. This deployment exposes Influxdb API to them.

## About `Magi`

`Magi` is an example machine that equips an IPMI with Redfish support.
