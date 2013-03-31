# time-select
Basic JavaScript implementation of a "time specific" version of iOS:s UIDatePicker.

## Usage
```javascript
var
  now = new Date(),
  selectorEl = document.querySelector(".js-time-select");

// scroll to the time represented in `now` and store `now` as selected time for later access
selectorEl.setTime(now);  // takes a Date object as parameter

// get selected time
selectorEl.getTime();  // returns a Date object
```

## Demo
http://time-select.herokuapp.com
