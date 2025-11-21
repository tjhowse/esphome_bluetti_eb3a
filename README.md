# ESPHome config for Bluetti EB3A

I use a Bluetti EB3A as a UPS for my home server and network gear. It works well,
however if the power goes out and the battery completely discharges, it does not
re-enable the AC and DC power outputs when the mains power turns on again.

This project communicates to an EB3A via bluetooth and, once per minute, turns on
the AC and DC power outputs. It also grants MQTT control and monitoring to everything
exposed on the EB3A's bluetooth interface.
