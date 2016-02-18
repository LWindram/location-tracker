# location-tracker

This script / LaunchDaemon combo allows for location based tracking of device usage.  Several parts were borrowed from other scripts, but I can't recall where they all came from.  If something looks familiar it's probably yours.

This was developed primarily because we have had several students misplace their devices.  iCloud location history is only maintained for 24 hours; this is often not a long enough duration when a computer is lost/stolen over the weekend.   Logs are maintained in perpetuity on the devices.

There is an associated Extension Attribute that pulls recent location history into Casper.  This is used for devices that aren't meant to leave the facility.  The current EA saves the most recent 10 locations, but can be set as needed.
