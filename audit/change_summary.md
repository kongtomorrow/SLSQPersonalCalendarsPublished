# Calendar Generation Succeeded

- Previous baseline: found
- Before events: 1268
- After events: 1267
- Delta: -1
- Added events: 3
- Removed events: 4
- Changed events: 9
- People affected by listed changes: 120

## Fixed Inconsistencies

None.

## Events By Kind

### Before

```json
{
  "COACHING": 1060,
  "FACULTY": 35,
  "FACULTY_CONCERTS": 25,
  "FACULTY_DAILY": 1,
  "MASTERCLASS": 22,
  "PARTICIPANT_DRESS_REHEARSAL": 52,
  "PELZER": 24,
  "REGISTRATION": 26,
  "SIGHT_READING": 8,
  "TRAVEL": 15
}
```

### After

```json
{
  "COACHING": 1060,
  "FACULTY": 35,
  "FACULTY_CONCERTS": 25,
  "FACULTY_DAILY": 1,
  "MASTERCLASS": 22,
  "PARTICIPANT_DRESS_REHEARSAL": 52,
  "PELZER": 23,
  "REGISTRATION": 26,
  "SIGHT_READING": 8,
  "TRAVEL": 15
}
```

### Added Examples
- `+` 2026-06-24 14:00:00-15:00:00 | Rehearsal: String Quintet | Dinkelspiel Stage | Nate Strothkamp, Raunak Kumar, Jeremy Klein, Starla Breshears, Gabriel Irazabal | COACHING
- `+` 2026-06-24 15:15:00-16:15:00 | Paul Coaching: String Quintet | Dinkelspiel Stage | Nate Strothkamp, Raunak Kumar, Jeremy Klein, Starla Breshears, Gabriel Irazabal | COACHING
- `+` 2026-06-24 15:15:00-16:15:00 | String Quintet | Dinkelspiel Stage | Paul Wiancko | COACHING

### Removed Examples
- `-` 2026-06-24 15:15:00-16:15:00 | Rehearsal: String Quintet | Dinkelspiel Stage | Nate Strothkamp, Raunak Kumar, Jeremy Klein, Starla Breshears, Gabriel Irazabal | COACHING
- `-` 2026-06-24 14:00:00-15:00:00 | Paul Coaching: String Quintet | Dinkelspiel Stage | Nate Strothkamp, Raunak Kumar, Jeremy Klein, Starla Breshears, Gabriel Irazabal | COACHING
- `-` 2026-06-24 14:00:00-15:00:00 | String Quintet | Dinkelspiel Stage | Paul Wiancko | COACHING
- `-` 2026-06-23 14:15:00-14:30:00 | Adam Pelzer appointment | Campbell Recital Hall | Anthony Chukhlov | PELZER

### Changed Event Examples
- Changed fields: time
- Before:
  - `2026-06-27 10:30:00-11:30:00 | Owen Coaching: Virtuosa Trio | 228 | Chia Ying Lee, Yi Ying Wei, Chiao Hui Chang | COACHING`
- After:
  - `2026-06-27 15:30:00-16:30:00 | Owen Coaching: Virtuosa Trio | 228 | Chia Ying Lee, Yi Ying Wei, Chiao Hui Chang | COACHING`
- Changed fields: time
- Before:
  - `2026-06-27 10:30:00-11:30:00 | Virtuosa Trio | 228 | Owen Dalby | COACHING`
- After:
  - `2026-06-27 15:30:00-16:30:00 | Virtuosa Trio | 228 | Owen Dalby | COACHING`
- Changed fields: participants
- Before:
  - `2026-06-23 21:00:00-22:30:00 | The Musicians of the String Quartet: | Braun Lounge | Alexi Kenney, Anthony Manzo, Ayane Kozasa, Daniel Phillips, Dimitri Murrath, +115 | FACULTY`
- After:
  - `2026-06-23 21:00:00-22:30:00 | The Musicians of the String Quartet: | Braun Lounge | Alexi Kenney, Anthony Manzo, Ayane Kozasa, Daniel Phillips, Dimitri Murrath, +14 | FACULTY`
- Changed fields: time
- Before:
  - `2026-06-25 15:15:00-15:35:00 | DR: The Quarktet | Campbell Recital Hall | Owen Dalby | PARTICIPANT_DRESS_REHEARSAL`
- After:
  - `2026-06-27 12:30:00-12:50:00 | DR: The Quarktet | Campbell Recital Hall | Owen Dalby | PARTICIPANT_DRESS_REHEARSAL`
- Changed fields: time
- Before:
  - `2026-06-25 15:15:00-15:35:00 | Dress Rehearsal | Campbell Recital Hall | Emil Ma, Chung-Pei Ma, Derek Katz, Ari Freed | PARTICIPANT_DRESS_REHEARSAL`
- After:
  - `2026-06-27 12:30:00-12:50:00 | Dress Rehearsal | Campbell Recital Hall | Emil Ma, Chung-Pei Ma, Derek Katz, Ari Freed | PARTICIPANT_DRESS_REHEARSAL`
- Changed fields: participants
- Before:
  - `2026-06-23 12:00:00-12:15:00 | Adam Pelzer appointment | Campbell Recital Hall | Anna Soper | PELZER`
- After:
  - `2026-06-23 12:00:00-12:15:00 | Adam Pelzer appointment | Campbell Recital Hall | Chung-Pei Ma | PELZER`
- Changed fields: participants
- Before:
  - `2026-06-23 14:00:00-14:15:00 | Adam Pelzer appointment | Campbell Recital Hall | Leslie Ashworth | PELZER`
- After:
  - `2026-06-23 14:00:00-14:15:00 | Adam Pelzer appointment | Campbell Recital Hall | Anthony Chukhlov | PELZER`
- Changed fields: participants
- Before:
  - `2026-06-23 14:45:00-15:00:00 | Adam Pelzer appointment | Campbell Recital Hall | Chung-Pei Ma | PELZER`
- After:
  - `2026-06-23 14:45:00-15:00:00 | Adam Pelzer appointment | Campbell Recital Hall | Ria Honda | PELZER`
- Changed fields: participants
- Before:
  - `2026-06-23 15:00:00-15:15:00 | Adam Pelzer appointment | Campbell Recital Hall | Meg Lamm | PELZER`
- After:
  - `2026-06-23 15:00:00-15:15:00 | Adam Pelzer appointment | Campbell Recital Hall | Elisabeth Heremans | PELZER`

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
