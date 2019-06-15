## Scheduled Export of Data to File v1.0

## Overview

This is a plugin helps with exporting Splunk data to file for backup purposes.
The plugin fills the need for a backup solution that is missing especially when running Splunk as a single instance.

It is implemented as an alert action that uses a python scrypt to move the search output to the desired location.
Note that there is a time limit on alert action to execute. So prevent heaving queries or export very big batches of data at once.

## Dependencies

* Splunk 6.3+
* Tested on Windows 

## Setup

* Untar the release to your $SPLUNK_HOME/etc/apps directory
* Restart Splunk