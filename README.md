# SBFSpot output plugin for [deye-inverter-mqtt]

This repo provides a output plugin for the great work here:
[deye-inverter-mqtt]: https://github.com/kbialek/deye-inverter-mqtt/

It [deye-inverter-mqtt] to read all relevant data and publishes it to MQTT in the same json format as used by 
https://github.com/SBFspot/SBFspot

This way existing monitoring tools (e.g. influxdb/Grafana dashboards) built on top of this can still be used