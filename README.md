# Splunk Export Data plugin
This is a Splunk plugin providing a custom alert script to export data to disk.
The main reason for this plugin is to have a backup solution for a single instance Splunk configuration.

Without this tool the advise of Splunk is to use low level disk copy tools to:
* Rotate the hot bucket to warm buckets and back them up. 
* Or to use low level disk copy tools to back up the hot bucket.
In either case it is complicated and/or still leaves the data in the hot bucket vulnerable.