Simple Process Monitor
======================

I just want a panel across the top of a screen (just a window, i3 can handle the
fancy stuff) that contains processes that were started from the command line,
and that have been running for some period of time.  Maybe change colors as they
age.  Some indication when they terminate (color change and they stick around
for a little bit).  Show how long they've been running.

Use: https://github.com/fyne-io/fyne

Requirements:
- API for adding processes to watch list (curl? unix pipe?)
    - Ignore if they terminate under a threshold?
- Refresh process status, runtime
- Color-coded by age
- Beep when process terminates
