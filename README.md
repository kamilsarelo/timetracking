# Dynatrace timetracking via Excel spreadsheet

from 2019-04-01 on you'll **need two things**:
- my [**Excel spreadsheet**](./spreadsheet/spreadsheet.xlsx) v16+ to track your working times easily
- my **bookmarklet** to book your times from the spreadsheet to Timecockpit

## How to create the bookmarklet

1) create a bookmark in your browser with the following code as location/url (this is the bookmarklet):
 ```javascript
 javascript:void function(){alert('hello');}();
 ```

2) click the bookmarklet to use it (will forward to Timecockpit first, in case not open yet)

3) copy Timecockpit-strings from the spreadsheet and paste them into the bookmarklet's window

4) click BOOK
