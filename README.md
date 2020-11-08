# seatalk_convert
Script that reads 9-bits seatalk 1 messages from any GPIO port using bitbanging, and converts it into NMEA0198 messages.

Based on https://github.com/MatsA/seatalk1-to-NMEA0183

Only two messages are currently created: VHW and MTW.

VHW contains both Speed Through Water, coming from one instrument, and Compass Heading, coming from the other.

Water temperature MTW is also created.

