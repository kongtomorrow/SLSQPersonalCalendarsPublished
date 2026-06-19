# Calendar Generation Succeeded

- Previous baseline: found
- Before events: 1152
- After events: 1165
- Delta: +13
- Added events: 15
- Removed events: 2
- Changed events: 3
- People affected by listed changes: 120

## Fixed Inconsistencies

None.

## Events By Kind

### Before

```json
{
  "COACHING": 1039,
  "FACULTY": 35,
  "FACULTY_CONCERTS": 25,
  "FACULTY_DAILY": 1,
  "MASTERCLASS": 9,
  "PELZER": 20,
  "SIGHT_READING": 8,
  "TRAVEL": 15
}
```

### After

```json
{
  "COACHING": 1042,
  "FACULTY": 35,
  "FACULTY_CONCERTS": 25,
  "FACULTY_DAILY": 1,
  "MASTERCLASS": 19,
  "PELZER": 20,
  "SIGHT_READING": 8,
  "TRAVEL": 15
}
```

### Added Examples
- `+` 2026-06-27 14:30:00-15:30:00 | Pam Coaching: 8tet with Dolores 4 | Braun Rehearsal Hall | Gregorio Lopes, Ko Hayashi, Ron Ho, Mark Siegel, Cary Chin, +3 | COACHING
- `+` 2026-06-27 14:30:00-15:30:00 | 8tet with Dolores 4 | Braun Rehearsal Hall | Pamela Frank | COACHING
- `+` 2026-06-27 14:30:00-15:30:00 | 8tet with Dolores 4 (cover Pam) | Braun Rehearsal Hall | Anthony Manzo | COACHING
- `+` 2026-06-24 21:00:00-22:30:00 | Cello-ssus Reading! | Braun Rehearsal Hall | Alexi Kenney, Anthony Manzo, Ayane Kozasa, Daniel Phillips, Dimitri Murrath, +115 | FACULTY
- `+` 2026-06-21 12:45:00-14:15:00 | Dvorak 6tet Faculty Rehearsal #2 | Campbell Recital Hall | Owen Dalby, Daniel Phillips, Steven Tenenbom, William Coleman, Paul Wiancko, +1 | FACULTY_CONCERTS
- `+` 2026-06-24 16:30:00-18:00:00 | Coaching Masterclass 2B | Dinkelspiel Stage | Ayane Kozasa, Hannah Collins | MASTERCLASS
- `+` 2026-06-24 16:30:00-18:00:00 | Playing Masterclass 2B | Dinkelspiel Stage | Jihyun Baik, Oliver Leitner, Lourdes Pinney, Colin Guan, Luke Henderson, +8 | MASTERCLASS
- `+` 2026-06-24 16:30:00-18:00:00 | Coaching Masterclass 2C | Braun Rehearsal Hall | Dimitri Murrath, Anthony Manzo, Pedja Muzijevic | MASTERCLASS
- `+` 2026-06-24 16:30:00-18:00:00 | Playing Masterclass 2C | Braun Rehearsal Hall | Chia Ying Lee, Yi Ying Wei, Chiao Hui Chang, Shawn Barnett, Ari Le, +2 | MASTERCLASS
- `+` 2026-06-25 16:00:00-17:30:00 | Coaching Masterclass 3A | Campbell Recital Hall | Owen Dalby, Anthony Manzo, Paul Wiancko | MASTERCLASS
- `+` 2026-06-25 16:00:00-17:30:00 | Playing Masterclass 3A | Campbell Recital Hall | Miles Chan, Anna Soper, Eric Cooper, Griffin Glenn, Jasper Jian, +4 | MASTERCLASS
- `+` 2026-06-25 16:00:00-17:30:00 | Coaching Masterclass 3B | Dinkelspiel Stage | Todd Palmer, Alexi Kenney, William Coleman | MASTERCLASS
- `+` 2026-06-25 16:00:00-17:30:00 | Playing Masterclass 3B | Dinkelspiel Stage | Christine Choi, Bruce Yu, Jessica Seeliger, Warren Wu, Emil Ma, +8 | MASTERCLASS
- `+` 2026-06-25 16:00:00-17:30:00 | Coaching Masterclass 3C | Braun Rehearsal Hall | John Novacek, Daniel Phillips, Hannah Collins | MASTERCLASS
- `+` 2026-06-25 16:00:00-17:30:00 | Playing Masterclass 3C | Braun Rehearsal Hall | Ko Hayashi, Ron Ho, Cary Chin, Jim Zehnder, Gregorio Lopes, +11 | MASTERCLASS

### Removed Examples
- `-` 2026-06-24 21:00:00-22:30:00 | Cello-suss Reading! | Braun Rehearsal Hall | Alexi Kenney, Anthony Manzo, Ayane Kozasa, Daniel Phillips, Dimitri Murrath, +115 | FACULTY
- `-` 2026-06-21 13:00:00-14:30:00 | Dvorak 6tet Faculty Rehearsal #2 | Campbell Recital Hall | Owen Dalby, Daniel Phillips, Steven Tenenbom, William Coleman, Paul Wiancko, +1 | FACULTY_CONCERTS

### Changed Event Examples
- Changed fields: participants
- Before:
  - `2026-06-24 16:30:00-18:00:00 | Masterclass 2A, 2B 2C | Campbell Recital Hall or Dinkelspiel Stage or Location | Luke Henderson, Isaac Park, James Preucil, Ian Maloney, Jeanel Liango, +105 | MASTERCLASS`
- After:
  - `2026-06-24 16:30:00-18:00:00 | Masterclass 2A, 2B 2C | Campbell Recital Hall or Dinkelspiel Stage or Location | Jeanel Liango, Jérôme Chiasson, Celia Morin, Maya Enstad, Shintaro Taneda, +72 | MASTERCLASS`
- Changed fields: participants
- Before:
  - `2026-06-24 16:30:00-18:00:00 | Playing Masterclass 2A | Campbell Recital Hall | Aaron Wilk, Misha Rafiee, Gregorio Lopes, James Welch, Persis Drell, +2 | MASTERCLASS`
- After:
  - `2026-06-24 16:30:00-18:00:00 | Playing Masterclass 2A | Campbell Recital Hall | Aaron Wilk, Misha Rafiee, Gregorio Lopes, James Welch, Persis Drell, +10 | MASTERCLASS`
- Changed fields: participants
- Before:
  - `2026-06-25 16:00:00-17:30:00 | Masterclass 3A, 3B, 3C | Campbell Recital Hall or Dinkelspiel Stage or Braun Rehearsal Hall | Luke Henderson, Isaac Park, James Preucil, Ian Maloney, Jeanel Liango, +115 | MASTERCLASS`
- After:
  - `2026-06-25 16:00:00-17:30:00 | Masterclass 3A, 3B, 3C | Campbell Recital Hall or Dinkelspiel Stage or Braun Rehearsal Hall | Luke Henderson, Isaac Park, James Preucil, Ian Maloney, Jeanel Liango, +68 | MASTERCLASS`

## Affected People

Aaron Wilk, Abigail Rogers, Alex Hwang, Alex Li, Alexi Kenney, Anna Soper, Anne Scott, Anthony Chukhlov, Anthony Manzo, Ari Freed, Ari Le, Ayane Kozasa, Ayoun Alexandra Kim, Ben Parks, Benjamin Chen, Beverly Fu, Bruce Yu, Cary Chin, Celia Morin, Chia Ying Lee, Chiao Hui Chang, Christine Choi, Christopher Lin-Brande, Chung-Pei Ma, Cindy Mong, Cindy Wang, Colin Guan, Cristina Ruotolo, Cyrus Behroozi, Daiyao Zhang, Daniel Phillips, Derek Katz, Derek Wu, Dimitri Murrath, Dustin Breshears, Elisabeth Heremans, Emil Ma, Emma Spellman, Eric Cheng, Eric Cooper, Gabriel Irazabal, Gregorio Lopes, Griffin Glenn, Haeun Nam, Hannah Collins, Hilary Meltzer, Howard Nelson, I-han Chou, Ian Maloney, Isaac Park, Isabella Fulford, JK Hunt, James Preucil, James Welch, Jasper Jian, Jeanel Liango, Jennah Delp Somers, Jennie Yang, Jeremy Klein, Jessica Seeliger, Jihyun Baik, Jim Chou, Jim Zehnder, Jocelyn Lamm Startz, John Novacek, Jon Lee, Jérôme Chiasson, Katie Behroozi, Ken Ferry, Ko Hayashi, Laura Shifley, Laurence Lewis, Lesley Robertson, Leslie Ashworth, Leyan Lo, Lloyd Minor, Lois Harder, Lourdes Pinney, Luke Henderson, Marandi Hostetter, Marie Christine Lopez, Mark Siegel, Maya Enstad, Meg Lamm, Melissa Chu, Melissa Lam, Miles Chan, Minsu Longiaru, Misha Rafiee, Monica Anuforo, Nate Strothkamp, Neir Eshel, Nina Lee, Nina Monfredo, Norman Truong, Oliver Leitner, Olivia Tam, Owen Dalby, Pamela Frank, Paul Wiancko, Pedja Muzijevic, Persis Drell, Raunak Kumar, Ria Honda, Ron Ho, Samantha Ching, Seth Novatt, Shawn Barnett, Sheila Chan, Shintaro Taneda, Starla Breshears, Stefan Leape, Stephen Prutsman, Steven Tenenbom, Thomas Xiong, Todd Palmer, Tyson Mao, Warren Wu, William Coleman, Yi Ying Wei

## Calendar Links

### Alexi Kenney
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/Alexi_Kenney.ics

### Anthony Manzo
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/Anthony_Manzo.ics

### Ayane Kozasa
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/Ayane_Kozasa.ics

### Daniel Phillips
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/Daniel_Phillips.ics

### Dimitri Murrath
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/Dimitri_Murrath.ics

### Hannah Collins
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/Hannah_Collins.ics

### Howard Nelson
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/Howard_Nelson.ics

### Jennah Delp Somers
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/Jennah_Delp_Somers.ics

### John Novacek
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/John_Novacek.ics

### Lesley Robertson
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/Lesley_Robertson.ics

### Nina Lee
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/Nina_Lee.ics

### Owen Dalby
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/Owen_Dalby.ics

### Pamela Frank
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/Pamela_Frank.ics

### Paul Wiancko
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/Paul_Wiancko.ics

### Pedja Muzijevic
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/Pedja_Muzijevic.ics

### Stephen Prutsman
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/Stephen_Prutsman.ics

### Steven Tenenbom
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/Steven_Tenenbom.ics

### Todd Palmer
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/Todd_Palmer.ics

### William Coleman
webcal://kongtomorrow.github.io/SLSQPersonalCalendarsPublished/calendars/William_Coleman.ics
