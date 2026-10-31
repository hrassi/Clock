# clock.py give real local time and date and auto synchronyse
#
# USE:
#       import clock
#       print(clock.get_time())
#       print(clock.get_date())
#       print(clock.get_date_time())
#       print(clock.get_day())
#


TIMEZONE_OFFSET = 2  # lebanon utc + 2 hours
DST_START = (3, 29)  # day light saving time 29 mars
DST_END = (10, 25)   # day light ending time 25 october
DST_OFFSET = 1       # the extra hour added during DST (during summer)

