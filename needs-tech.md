# Visit-counter technical needs

Scenario: Recover across restarts of the server that runs the visit-counter

  Given visit-counter runner
  When there is server restart
  Then it recovers visit-count
  
Scenario: Reconcile counts if the sensor is offline for a while
  
  Given sensor is offline
  When I click on count
  Then it reconciles counts
