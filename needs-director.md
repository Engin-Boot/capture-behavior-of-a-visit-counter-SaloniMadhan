# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays
  Given count of patient visits When I click on show visits
  Then displays patient visits day-wise  
Scenario: Compute parking slots to reserve for visiting specialists
  Given parking slots When visitor is visiting specialist
  Then reserves parking slot
  

