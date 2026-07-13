---
title: "Degraded Storefront API Performance"
url: "https://status.nacelle.com/incidents/0t9bsklkd9q7"
date: "2023-11-11"
feed_url: "https://status.nacelle.com/history.atom"
---
Nov 11 , 23:30 UTC Resolved - Between 6:26 PM ET and 7:21 PM ET, Nacelle experienced a spike of new requests that required Nacelle’s DevOps team to scale additional Kubernetes pods. While these new pods were scaling up, the API experienced degraded performance (e.g., long latencies). The root cause of the issue was how Nacelle's custom schema fetching works across new additions to our GraphQL interface.
