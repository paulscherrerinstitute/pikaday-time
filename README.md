Pikaday - With Time Picker as an ES6 module
========

### Changes from [Owen Mead-Robin's Pikaday][owen pika]

- Converted to ES6 module
- *moment* is now a full dependency

### Key Config Changes

```javascript
showTime: true
showSeconds: false
use24hour: false
incrementHourBy: 1
incrementMinuteBy: 1
incrementSecondBy: 1
autoClose: true
```

### Time support, including milliseconds, added to [dbushell/Pikaday][david Pika]

This fork allows the user to specify the time along with their date. Done so by adding a couple select inputs to manipulate the date Pikaday is generating.

* Used to set time aspects of date.
* Will not change the currently selected date.
* If no date is selected, will select today. Any of the arguments may be null, and will not affect the date.


## Authors

* Christof Zellweger
* Daniel J. Lauk
* Owen Mead-Robins [http://www.owenmead.com/][owenmead]

[david Pika]:   https://github.com/dbushell/Pikaday                              "Pikaday (@dbushell)"
[owen Pika]:    https://github.com/owenmead/Pikaday                              "Pikaday (@owenmead)"
[owenmead]:     http://owenmead.com/                                             "owenmead.com"
