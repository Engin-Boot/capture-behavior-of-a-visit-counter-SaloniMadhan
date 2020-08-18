# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given count of patient visits<br>
  When I click on show visits<br>
  Then displays patient visits day-wise<br>
  
Scenario: Compute parking slots to reserve for visiting specialists

  Given parking slots<br>
  When visitor is visiting specialist<br>
  Then reserves parking slot<br>
  

