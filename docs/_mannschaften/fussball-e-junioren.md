---
schemadotorg:
  "@context": "https://schema.org"
  "@type": SportsTeam
  name: E-Junioren
  sport: soccer
  image:
    "@type":  ImageObject
    contentUrl: https://icon-library.net//images/image-placeholder-icon/image-placeholder-icon-16.jpg
    caption: Platzhalter für das Mannschaftsbild
  coach:
    - "@type":  Person
      url: "%URL%/personen/christoph-staudinger.html"
    - "@type":  Person
      url: "%URL%/personen/etienne-wegner.html"
  event:
    "@type":  Event
    name: Training
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

