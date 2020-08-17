# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given a month of data of patient visits
  When show patient visits is clicked
  Then patient visits across working days and holidays is displayed

Scenario: Compute parking slots to reserve for visiting specialists

  Given two parking slots one for hospital staff and other for all visitors 
  When visitor is visiting specialist
  Then a parking slot gets reserved for him
