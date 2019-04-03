this home assistant sensor is to read info from the XS Mastervolt invertors and is only tested with the XS2000.
To configur this add the following to your configuration.yaml :

sensor:
  - platform: MasterVoltXS
    TCP_PORT: 5678
    TCP_IP: 192.168.1.173
    RECONNECT_INTERVAL: 10

All field are required.