# REAL TIME AIR POLLUTION DASHBOARD
A use-case measuring air quality with sensor around a factory to showcase the ability of Taipy to dashboard streaming data.

1. Run receiver.py
`python receiver.py`

This should open a dashboard on the web
2. Run sender.py
`python sender.py`

This should send the data to the dashboard

## Processes

The data is generated on another server and sent to this Taipy application via a WebSocket.

Taipy then processes the data and displays it on a dashboard.

The dashboard is updated in real time as new data is received.