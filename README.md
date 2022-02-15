# rustybrewer

Are you coffee lover? Do you own a single boiler coffee brew machine?

Simple thermocouple You'll find a complete DIY setup here.

- PID software (Rust)
  - Prometheus metrics
  - HTTP Endpoint
- Control software (Rust)
  - Mode 0 standby
  - Mode 1 warm up, keep constact boiler temperature (95° C / 203° F)
  - Mode 2 brew, use additional heating vs. cold water pump
  - Mode 3 steam
- Discord Bot turn and off the brewer when you are far away from the machine (Deno Typescript)
  - uses Prometheus metrics and HTTP endpoint
- Incremental agile hardware rework
  - Max 4h without espresso!
  - Component list 

