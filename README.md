# seatalk_convert
Script that reads 9-bits seatalk 1 messages from any GPIO port using bitbanging, and converts it into NMEA0183 messages.

Based on https://github.com/MatsA/seatalk1-to-NMEA0183

Only two NMEA sentences are currently created: VHW and MTW.

VHW sentences contain both Speed Through Water, coming from one instrument, and Compass Heading, coming from the other.

Water temperature MTW sentences are also created because I could, not because I really use it.
