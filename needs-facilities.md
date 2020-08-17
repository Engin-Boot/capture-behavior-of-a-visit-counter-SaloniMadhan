# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given visitor data on a day basis
  When i click on get visitor trend for the desired week
  Then it reports visitor trend during that week of operation

Scenario: Alert when seating capacity is full

  Given a threshold value for seating capacity
  When current capacity touches the threshold value
  Then an alert is pushed
