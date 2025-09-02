#sample query to invoke weather.py server

@weather.get_alerts state="CA" event_filter="heat" limit=5 include_expires=true

@weather.get_alerts state="WA" limit=8
