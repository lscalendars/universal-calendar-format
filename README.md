universal-calendar-format
=========================

Documentation and schemes for the universal calendar format (ucr)

A few ideas of its use:
 * create a calendar-translation (c19n) library that can be used by web developpers to automatically translate their calendars (like i18n). For instance jquery-datepicker could optionally interface with c19n, so that
   * developers wanting to print a specific calendar just call $(#mycalendar).c19n('tibetan') to print a tibetan calendar instead of a gregorian one
   * a browser extension (or more) could be developped to automatically translate all calendars/datepickers seen by the user
 * create a database of calendars
 * change the main calendar applet of the OS so that users see the calendar they want
 * build apps to see specific calendars and compare them
