# List of changes in alfa versions

This is list of test/experiment firmware, with changes included:

### NAMF-2020-37a5

* SDS011 code moved to new
* sensor shows both time from last measurement and time left to next one

### NAMF-2020-37a4 
* sending to influx FW version and update channel
* always send to influx SDS results (when sensor is enabled), no reading is sent as -1

### NAMF-2020-37a3

* new communication with SDS (ported from Sensor Community fw, branch master on March 31st)