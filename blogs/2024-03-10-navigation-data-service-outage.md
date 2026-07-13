---
title: "Navigation Data Service Outage"
url: "https://status.nacelle.com/incidents/hn64w8cln67b"
date: "2024-03-10"
feed_url: "https://status.nacelle.com/history.atom"
---
Mar 10 , 16:00 UTC Resolved - Duration: 3/10 from ~9:00 am - 10:00 am PT (~1 hour) Issue: Starting at ~9:00 am PT on 3/10, some merchant builds failed due to 500 responses when fetching navigation data from the Storefront API. The navigation data service had encountered scaling issues that resulted in a lack of enough replicas being available for the volume of requests. Solution: By ~10:00 am PT, existing self-healing services had allowed navigation data service to stabilize and handle all incoming traffic.
