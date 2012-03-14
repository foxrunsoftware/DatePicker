# DatePicker

Yet another jQuery-based date picker!  This date picker provides an easy way of creating both single and multi-viewed calendars capable of accepting single, range, and multiple selected dates.  Easy to style, with two example styles provided: an attractive 'dark' style, and a Google Analytics-like 'clean' style.

## Quick start

Download the latest release, and jQuery.

    <script type="text/javascript" src="/js/jquery/jquery.js"></script>
    <script type="text/javascript" src="/js/datepicker/js/datepicker.js"></script>
    <link rel="stylesheet" media="screen" type="text/css" href="/js/datepicker/css/base.css" />
    <link rel="stylesheet" media="screen" type="text/css" href="/js/datepicker/css/clean.css" />
    
    <div id="simple-calendar"></div>
    
    <script type="text/javascript">
      $('#simple-calendar').DatePicker({
        mode: 'single',
        inline: true,
        date: new Date()
      });
    </script>

<img src="https://github.com/foxrunsoftware/DatePicker/blob/master/examples/screenshot-1.png?raw=true" />

Take a look at the [examples page](http://foxrunsoftware.github.com/DatePicker/) for live, and additional examples.  Then visit the [API reference page](http://foxrunsoftware.github.com/DatePicker/reference.html).

## Bug tracker

Have a bug? Please create an issue here on GitHub!

https://github.com/foxrunsoftware/DatePicker/issues

## Changelog

#### 1.0.0 - 3/12/2012 ####
* Initial Release
* Ripped out the built-in date formatter, this should be handled by the client
* Removed the built-in parseDate functionality
* Removed references to the 'week' column
* Styled away the 'not in month' date cells
* Split stylesheet into base.css to allow easier styling, and dark.css as the first full style
* Added 'clean' style similar to Google Analytics date picker
* Greyed out future dates for clean style
* Removed the excessive left/right arrows from multi-month calendars
* Highlight current date
* Calendar month title: clicking when in 'range' mode selects the entire month.  Clicking in single/multiple mode swaps between the monthly/yearly view unless there are multiple calendars
* Refactored code for readability
* Renamed options, renamed/refactored callbacks
* Commented code

## License/Credits

Copyright 2012, Justin Stern (www.foxrunsoftware.net)

Dual licensed under the MIT or GPL Version 2 licenses.

This project is based on DatePicker from http://www.eyecon.ro/datepicker/
This project is distinct from and not affiliated with the jquery.ui.datepicker