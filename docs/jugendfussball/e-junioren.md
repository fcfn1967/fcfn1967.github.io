---
layout: page
schemadotorg:
  "@context": "https://schema.org"
  "@type": WebPage
  name: E-Junioren
  image:
    "@type":  ImageObject
    contentUrl: https://via.placeholder.com/640x360.png?text=Mannschaftsbild
    url: https://placeholder.com
  about:
    "@type": SportsTeam
    sport: Fussball
    name: E-Junioren
    coach:
      - "@type":  Person
        url: "%URL%/personen/christoph-staudinger.html"
      - "@type":  Person
        url: "%URL%/personen/etienne-wegner.html"
    event:
      - "@type":  Event
        name: Training
        location:
          "@type": Place
          url: "%URL%/orte/stadion-berufsschulzentrum.html"
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

