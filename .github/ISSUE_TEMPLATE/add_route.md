---
name: Add route request
about: Add new known route
title: Add Route
labels: new route
asignees: ''

---

**Add Route**
Add details as outlined below

Region: NORTH/WEST/SOUTH/EAST/OTHERS
```
{
      "busNumber": "6A",
      "towards": [
        {
		"destination": "Sepanggar",
		"route": "https://maps.app.goo.gl/L1vjrHjVPSDcCMhc6",
		"notes":"complete"
        },
        {
		"destination": "Kota Kinabalu",
          	"route": "https://maps.app.goo.gl/Fv4ZyMjG3pCuPdsv5",
		"notes":"complete"
        }
      ],
      "remark": "wait until full"
    }
```
For `notes`, there are 3 states to this primarily for the google maps route; `undef` being not confirmed, `partial` being route is known but start/end of route are not known, `complete` having all of their route information are 100% reliable
