# sample query to invoke weather.py server

#Commands:

  @weather.ping
  
  @weather.get_alerts state="CA" [event_filter="heat"] [limit=5] [include_expires=true]
  
  clear   — clear history
  
  exit    — quit

# Examples:

  @weather.get_alerts state="CA"
  
  @weather.get_alerts state="CA" event_filter="heat" limit=5 include_expires=true
  
  @weather.get_alerts state="WA" limit=8
