---
layout: page
schemadotorg:
  "@context": "https://schema.org"
  "@type": SportsTeam
  name: E-Junioren
  sport: Fussball
  image:
    "@type":  ImageObject
    contentUrl: https://via.placeholder.com/640x360.png?text=Mannschaftsbild
    url: https://placeholder.com
  coach:
    - "@type":  Person
      url: "%URL%/personen/christoph-staudinger.html"
    - "@type":  Person
      url: "%URL%/personen/etienne-wegner.html"
  event:
    - "@type":  Event
      name: Training
      location: | 
        Stadion Berufsschule   
        Steinbeisstr. 10  
        88046 Friedrichshafen
      eventSchedule:
        - "@type":  Schedule
          repeatFrequency:  P1W
          startTime:  "16:45"
          endTime:  "18:15"
          byDay: https://schema.org/Monday
        - "@type":  Schedule
          repeatFrequency:  P1W
          startTime:  "16:45"
          endTime:  "18:15"
          byDay: https://schema.org/Wednesday
---

