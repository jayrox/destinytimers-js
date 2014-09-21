Destiny Timers
================
This a public repo containing the timer JSON file used by the Destiny Timers mobile app. Contributions with fixes 
to times, and the addition of missing events are more than welcome!

###Contributing
Fork this repository and submit your contribution as a pull request. We also accept contributions in the form of 
new issues on GitHub.

###Format
The app currently accepts 3 types of events, these are identified by a type parameter. The start/end times are measured
as second offsets based on the type. If the type is hourly (such as a public event), the offset is from the beginning
of the hour. If the type is measured in days, the offset is from the stroke of midnight.

All times are UTC.