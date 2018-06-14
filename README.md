# PowerMonitor
Inline Power Monitor

Requirements
1. Adafruit Huzzah Feather https://www.adafruit.com/product/2821
  You may be able to use other boards but this project was built using this board.
2. NCD.io Single channel current monitor https://store.ncd.io/product/1-channel-on-board-97-accuracy-70-amp-ac-current-monitor-with-iot-interface/  I am using the 20 amp version but you could use others.
3. NCD.io Feather Adapter https://store.ncd.io/product/feather-to-iot-adapter-for-particle-and-feather-modules/
4. Influx DB instance - I am using InfluxDB in Docker on UnRaid. This is not required but I will not cover this part in great detail.
5. Grafana Instance - I am using Grafana in Docker on UnRaid. This guide will not cover it in great detail.


Power Meter-1523816441559.json <- this is the JSON file you can use to import the dashboard into Grafana.
Images Direcotry - In there I have several screen shots of the dashboard and the settings used.


`https://www.reddit.com/r/homelab/comments/8r3w0f/homebrew_power_monitor_for_rack/`
`https://www.thingiverse.com/thing:2961022`
`https://grafana.iceboxserver.com/d/P4bdxQmik/power-meter?refresh=5m&orgId=1`
