# FindMyiPhone
Locates all devices associated with an iCloud account. No user notification, pretty, pure python, quick, fast, accurate. Works for any account, including 2SV/2FA. This program will also work with a FMIP token that is extracted from the FindMyiPhone App on the iPhone. 

Device locations will now be opened in google maps on the default web browser if GUI is available (thank you **@KOWLOR**)

# Usage 

***python FMIP.py***

```
INPUT: Apple ID 

INPUT: Password
```
```
OUTPUT:

Sent location beacon to [3] devices

Awaiting response from iCloud...
(John Doe | 1234567[DSID]) -> Found 3 Devices
```
```
Device [1]

Model: MacBook Pro 13"

Name: Johns's MacBook Pro

Latitude, Longitude: <22.000000000;-22.000000000>

Opening location in web browser!

Battery: 0.4126002 & NotCharging

Located at: Monday, September 19 at 11:51:44 (0m 5s ago)
```
```

Device [2]

Model: iPhone 5s

Name: John's iPhone

Latitude, Longitude: <22.000000000;-22.000000000>

Opening location in web browser!

Battery: 1.0 & Charged

Located at: Monday, September 19 at 11:51:45 (0m 4s ago)

```
```
Device [3]

Model: MacBook Pro 15"

Name: John's MacBook Pro

Latitude, Longitude: <22.000000000;-22.000000000>

Opening location in web browser!

Battery: 0.6817946 & NotCharging

Located at: Monday, September 19 at 11:51:44 (0m 5s ago)
```
