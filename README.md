# aeg-inverter-monitor
Node-red Monitor tools for AEG AS-IR01 inverter. Sends info to public pvoutput site (https://pvoutput.org). Set API key and systemid in the flow (set payload headers). See pvoutput.org for an account. 

https://nodered.org/

# Node-Red script for monitoring a AEG inverter. 

Tested with AS-IR01 https://www.aeg-industrialsolar.de/product/inverters/singe-phase-inverters/one-phase-inverter/

Monitor AEG INVT is the main script that calls a subflow to do the modbus calls (Read AEG INVT)

Needed modules:
- node-red
- node-red-contrib-modbus
- node-red-contrib-moment
- node-red-contrib-time-range-switch
- node-red-dashboard


