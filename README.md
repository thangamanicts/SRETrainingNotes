# SRETrainingNotes

**Foundations of observability**

Methods of Monitoring

RED-  Request Oriented monitoring - Service Layer
-------------------------------------------------
1. Rate(Throughtput) - Request per second.
2. Errors: Failed requests ie HTTP 500
3. Duration: Latency or Transaction Response Time
   
USE Method - Resource Oriented  - Infrastructure Layer
----------------------------------------------------
1. Utilization i.e CPU Usage %, Disk Usage %
2. Saturation i.e Network Queue length Zero = Good
3. Errors i.e Disk Write Error Zero = Good

Four Signals Method introduced by Google for Service and Infrastructure
----------------------------------------------------------------------
1. Latency
2. Traffic(ThroughPut)
3. Errors
4. Staturtion

Core Web Vituals
----------------
1. Largest Contentful Paint (Perceived Page Load)
2. First Inout DelayI(Perceived Responsiveness)
3. Cumulative Layout Shift(Perceived Stability)
   
