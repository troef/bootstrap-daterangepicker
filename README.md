# Google Analytics like datepicker for Bootstrap

This fork aims to build a Google Analytics like datepicker. This means we are adding a feature to select a 'comparing daterange'. This is a work in progress, feel free to add pull requests.

* Based on https://github.com/dangrossman/bootstrap-daterangepicker
* Added features:
    * Compare the selected date range with the previous period or the same periode last year. The resulting dateranges are available through the API using .startDate, .endDate, .compareStartDate and . compareEndDate
    * Google Analytics alike look and feel
* Work in progress
    * Select a comparing daterange on the calendar
    * Figure out what to do with features from the original like single datepicker, time picking
    * Sass

[[http://imgur.com/a/xH8yf|alt=Google Analytics like datepicker]]


# Original README

This date range picker component for Bootstrap creates a dropdown menu from which a user can
select a range of dates. I created it while building the UI for [Improvely](http://www.improvely.com), 
which needed a way to select date ranges for reports.

Features include limiting the selectable date range, localizable strings and date formats,
a single date picker mode, optional time picker (for e.g. making appointments or reservations),
and styles that match the default Bootstrap 3 theme.

## [Documentation and Live Usage Examples](http://www.daterangepicker.com)

## [See It In a Live Application](https://awio.iljmp.com/5/drpdemogh)

## License

This code is made available under the same license as Bootstrap. Moment.js is included in this repository
for convenience. It is available under the [MIT license](http://www.opensource.org/licenses/mit-license.php).

--

The MIT License (MIT)

Copyright (c) 2012-2016 Dan Grossman

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
