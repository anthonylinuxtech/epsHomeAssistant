# EPS / Homiris Home Assistant integration

The EPS integration provides connectivity with alarm systems based on [EPS](https://www.eps.fr/). Some other companies (ex: Homiris) distribute those systems.

It allows to get the state of your alarm system.

Use the following token to fill the token field : NHhSOG1LZFk5OFBRalpkNU1NUzJRNWZYWl9RYTpEajkwbF9IOGs3WGJvZ1pTbzl3MUxTemxOZ01h
For the ID it's your contract number ( You can find it on the documents provided to you at the time of subscription or on your invoices. )
And finally, the password is the password of your subscriber area.

This platform supports the following services:

- `alarm_control_panel.alarm_arm_away`
- `alarm_control_panel.alarm_arm_night`
- `alarm_control_panel.alarm_disarm`
