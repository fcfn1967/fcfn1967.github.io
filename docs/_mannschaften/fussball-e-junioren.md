---
schemadotorg:
  "@context": "https://schema.org"
  "@type": SportsTeam
  name: E-Junioren
  sport: soccer
  image:
    "@type":  ImageObject
    contentUrl: https://via.placeholder.com/640x480.png?text=Mannschaftsbild
  coach:
    - "@type":  Person
      url: "%URL%/personen/christoph-staudinger.html"
    - "@type":  Person
      url: "%URL%/personen/etienne-wegner.html"
  event:
    - "@type":  Event
      name: Training
      location: Stadion Berufsschule
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

