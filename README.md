TODO

- split out css and js files
- comment and understand css
- dbSync
    how to reflect edits made on db copied to local
    implement edits on local data that is already 'synced'
    points tab, get data from cloud
- style
    - too much bottom margin in landscape
    - minus button on counters on iphone not centered
- clean up editRecord. enforce datatype conservation better
- fix the formPicker situation. 
    - since it is global it can just call show() if we track what tab were on, then you dont need the after() callback
    - filter data on export by form? same on points view?


down the line
- automatic logs at certain locations
    get loc every five seconds. if connecting line crosses or is in geo area, log it. What to do about multiple useless logs while dwelling at a stop? Could make it log only if in motion? this might miss logging a stop w no passenger utilization where i still dwell
- load data in chunks for when there are lots of points?
- time display, speed display
- display custom aggregates of data in log view
- map view
- shared forms