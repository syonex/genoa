This is genoa

    GEneric NOtification Author/Arranger/Artist

intended for use with Nagios for formatting notifications.

It works nicely with tellitto.

Use genoa in your nagios object definitions something like thia:

define command {
    command_name host-by-email
    command_line genoa -s
}
define command {
    command_name host-by-pager
    command_line genoa -p -t
}


This distribution could use a little improvement
- the sample templates aren't (currently) installed for example

I wrote this at FreshBooks www.freshbooks.com
    #1 Cloud Accounting Specialist for Small Business Owners


Feedback and suggestions greatly appreciated.

John Sellens
software@syonex.com
