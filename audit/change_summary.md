# Calendar Generation Succeeded

- Previous baseline: found
- Before events: 1266
- After events: 1266
- Delta: +0
- Added events: 4
- Removed events: 4
- Changed events: 3
- People affected by listed changes: 21

## Fixed Inconsistencies

These documented consistency issues were not used this run and may be ready to remove:

- Dress rehearsal schedule coach assignments are missing or conflicting in faculty daily tabs

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
  "PELZER": 22,
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
  "PELZER": 22,
  "REGISTRATION": 26,
  "SIGHT_READING": 8,
  "TRAVEL": 15
}
```

### Added Examples
- `+` 2026-06-25 17:30:00-19:15:00 | Mendelssohn 6tet Faculty Rehearsal #2 (As You Wish) | Campbell Recital Hall | Daniel Phillips, William Coleman, Dimitri Murrath, Hannah Collins, Anthony Manzo, +1 | FACULTY_CONCERTS
- `+` 2026-06-26 11:00:00-11:20:00 | DR: Dolores Quintet | Campbell Recital Hall | Alexi Kenney | PARTICIPANT_DRESS_REHEARSAL
- `+` 2026-06-26 09:00:00-09:20:00 | DR: Katarina String Quartet | Campbell Recital Hall | Ayane (not present) | PARTICIPANT_DRESS_REHEARSAL
- `+` 2026-06-25 09:30:00-09:50:00 | DR: The Dolphins | Campbell Recital Hall | Lesley Robertson | PARTICIPANT_DRESS_REHEARSAL

### Removed Examples
- `-` 2026-06-25 19:00:00-20:00:00 | Mendelssohn 6tet Faculty Rehearsal #2 (As You Wish) | Campbell Recital Hall | Daniel Phillips, William Coleman, Dimitri Murrath, Hannah Collins, Anthony Manzo, +1 | FACULTY_CONCERTS
- `-` 2026-06-25 11:00:00-11:20:00 | DR: Dolores Quintet | Campbell Recital Hall | John Novacek | PARTICIPANT_DRESS_REHEARSAL
- `-` 2026-06-26 09:00:00-09:20:00 | DR: Katarina String Quartet | Campbell Recital Hall | Ayane Kozasa | PARTICIPANT_DRESS_REHEARSAL
- `-` 2026-06-25 09:30:00-09:50:00 | DR: The Dolphins | Campbell Recital Hall | Steven Tenenbom | PARTICIPANT_DRESS_REHEARSAL

### Changed Event Examples
- Changed fields: time
- Before:
  - `2026-06-26 13:45:00-14:05:00 | DR: Chane String Quartet | Campbell Recital Hall | William Coleman | PARTICIPANT_DRESS_REHEARSAL`
- After:
  - `2026-06-26 16:45:00-17:05:00 | DR: Chane String Quartet | Campbell Recital Hall | William Coleman | PARTICIPANT_DRESS_REHEARSAL`
- Changed fields: time
- Before:
  - `2026-06-26 13:45:00-14:05:00 | Dress Rehearsal | Campbell Recital Hall | Ria Honda, Christopher Lin-Brande, Nina Monfredo, Abigail Rogers | PARTICIPANT_DRESS_REHEARSAL`
- After:
  - `2026-06-26 16:45:00-17:05:00 | Dress Rehearsal | Campbell Recital Hall | Ria Honda, Christopher Lin-Brande, Nina Monfredo, Abigail Rogers | PARTICIPANT_DRESS_REHEARSAL`
- Changed fields: time
- Before:
  - `2026-06-25 11:00:00-11:20:00 | Dress Rehearsal | Campbell Recital Hall | Aaron Wilk, Misha Rafiee, Gregorio Lopes, James Welch, Persis Drell | PARTICIPANT_DRESS_REHEARSAL`
- After:
  - `2026-06-26 11:00:00-11:20:00 | Dress Rehearsal | Campbell Recital Hall | Aaron Wilk, Misha Rafiee, Gregorio Lopes, James Welch, Persis Drell | PARTICIPANT_DRESS_REHEARSAL`

## Affected People

Aaron Wilk, Abigail Rogers, Alexi Kenney, Anthony Manzo, Ayane (not present), Ayane Kozasa, Christopher Lin-Brande, Daniel Phillips, Dimitri Murrath, Gregorio Lopes, Hannah Collins, James Welch, John Novacek, Lesley Robertson, Misha Rafiee, Nina Monfredo, Pedja Muzijevic, Persis Drell, Ria Honda, Steven Tenenbom, William Coleman

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
