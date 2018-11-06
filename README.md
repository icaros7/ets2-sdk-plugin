# ETS2/ATS Telemetry Plugin

This is a fork of [the tweaked telemetry plugin](https://github.com/Funbit/ets2-sdk-plugin) (by Funbit) tweaked specially for [ETS2 Telemetry Web Server Korean Edition](https://github.com/icaros7/ets2-kor-telemetry-server).
 
# Version history

### Revision 10 (19th June 2016)

- implemented job information buffer to avoid unexpected reset when trailer is detached on the way

### Revision 9 (28th March 2016)

- refactored job information reset, should work a bit more stable

### Revision 8 (13th March 2016)

- fixed job information reset when job is done

### Revision 5 (13th June 2015)

- removed duplicated engine\_enabled property which was a duplicate for electric\_enabled property causing it not to work properly

### Revision 4 (23th May 2015)

- updated for SCS SDK 1.5
- added support for new telemetry data
- changed MMF name to "Local\\Ets2TelemetryServer"

# License

The MIT License (MIT)