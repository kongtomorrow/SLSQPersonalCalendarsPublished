# Calendar Generation Succeeded

- Previous baseline: found
- Before events: 1141
- After events: 1152
- Delta: +11
- Added events: 11
- Removed events: 0
- Changed events: 22
- People affected by listed changes: 25

## Fixed Inconsistencies

None.

## Events By Kind

### Before

```json
{
  "COACHING": 1028,
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

### Added Examples
- `+` 2026-06-23 14:30:00-15:30:00 | 8tet with Dolores 4 @ Dolores (cover Pam) | 776 Dolores St, Stanford, CA | Anthony Manzo | COACHING
- `+` 2026-06-25 14:30:00-15:30:00 | 8tet with Dolores 4 (cover Pam) | Braun Rehearsal Hall | Anthony Manzo | COACHING
- `+` 2026-06-23 13:15:00-14:15:00 | Quail 4tet @ Dolores (cover Pam) | 776 Dolores St, Stanford, CA | Lesley Robertson | COACHING
- `+` 2026-06-25 13:15:00-14:15:00 | Quail 4tet (cover Pam) | 102 | Lesley Robertson | COACHING
- `+` 2026-06-27 13:15:00-14:15:00 | Quail 4tet (cover Pam) | 102 | Lesley Robertson | COACHING
- `+` 2026-06-22 15:15:00-16:15:00 | Quartet 94 @ Dolores (cover Pam) | 776 Dolores St, Stanford, CA | Pedja Muzijevic | COACHING
- `+` 2026-06-24 15:15:00-16:15:00 | Quartet 94 @ Dolores (cover Pam) | 776 Dolores St, Stanford, CA | Pedja Muzijevic | COACHING
- `+` 2026-06-26 15:15:00-16:15:00 | Quartet 94 @ Dolores (cover Pam) | 776 Dolores St, Stanford, CA | Pedja Muzijevic | COACHING
- `+` 2026-06-22 14:00:00-15:00:00 | The Dolphins @ Dolores (cover Pam) | 776 Dolores St, Stanford, CA | Dimitri Murrath | COACHING
- `+` 2026-06-24 14:00:00-15:00:00 | The Dolphins (cover Pam) | 227 | Dimitri Murrath | COACHING
- `+` 2026-06-26 14:00:00-15:00:00 | The Dolphins (cover Pam) | 227 | Dimitri Murrath | COACHING

### Changed Event Examples
- Changed fields: title, location
- Before:
  - `2026-06-23 14:30:00-15:30:00 | Tony Coaching: 8tet with Dolores 4 | Braun Rehearsal Hall | Gregorio Lopes, Ko Hayashi, Ron Ho, Mark Siegel, Cary Chin, +3 | COACHING`
- After:
  - `2026-06-23 14:30:00-15:30:00 | Pam Coaching @ Dolores: 8tet with Dolores 4 | 776 Dolores St, Stanford, CA | Gregorio Lopes, Ko Hayashi, Ron Ho, Mark Siegel, Cary Chin, +3 | COACHING`
- Changed fields: title, location, participants
- Before:
  - `2026-06-23 14:30:00-15:30:00 | 8tet with Dolores 4 | Braun Rehearsal Hall | Anthony Manzo | COACHING`
- After:
  - `2026-06-23 14:30:00-15:30:00 | 8tet with Dolores 4 @ Dolores | 776 Dolores St, Stanford, CA | Pamela Frank | COACHING`
- Changed fields: title
- Before:
  - `2026-06-25 14:30:00-15:30:00 | Tony Coaching: 8tet with Dolores 4 | Braun Rehearsal Hall | Gregorio Lopes, Ko Hayashi, Ron Ho, Mark Siegel, Cary Chin, +3 | COACHING`
- After:
  - `2026-06-25 14:30:00-15:30:00 | Pam Coaching: 8tet with Dolores 4 | Braun Rehearsal Hall | Gregorio Lopes, Ko Hayashi, Ron Ho, Mark Siegel, Cary Chin, +3 | COACHING`
- Changed fields: participants
- Before:
  - `2026-06-25 14:30:00-15:30:00 | 8tet with Dolores 4 | Braun Rehearsal Hall | Anthony Manzo | COACHING`
- After:
  - `2026-06-25 14:30:00-15:30:00 | 8tet with Dolores 4 | Braun Rehearsal Hall | Pamela Frank | COACHING`
- Changed fields: title, location
- Before:
  - `2026-06-23 13:15:00-14:15:00 | Lesley Coaching: Quail 4tet | 102 | Katie Behroozi, Benjamin Chen, Ben Parks, Cyrus Behroozi | COACHING`
- After:
  - `2026-06-23 13:15:00-14:15:00 | Pam Coaching @ Dolores: Quail 4tet | 776 Dolores St, Stanford, CA | Katie Behroozi, Benjamin Chen, Ben Parks, Cyrus Behroozi | COACHING`
- Changed fields: title, location, participants
- Before:
  - `2026-06-23 13:15:00-14:15:00 | Quail 4tet | 102 | Lesley Robertson | COACHING`
- After:
  - `2026-06-23 13:15:00-14:15:00 | Quail 4tet @ Dolores | 776 Dolores St, Stanford, CA | Pamela Frank | COACHING`
- Changed fields: title
- Before:
  - `2026-06-25 13:15:00-14:15:00 | Lesley Coaching: Quail 4tet | 102 | Katie Behroozi, Benjamin Chen, Ben Parks, Cyrus Behroozi | COACHING`
- After:
  - `2026-06-25 13:15:00-14:15:00 | Pam Coaching: Quail 4tet | 102 | Katie Behroozi, Benjamin Chen, Ben Parks, Cyrus Behroozi | COACHING`
- Changed fields: participants
- Before:
  - `2026-06-25 13:15:00-14:15:00 | Quail 4tet | 102 | Lesley Robertson | COACHING`
- After:
  - `2026-06-25 13:15:00-14:15:00 | Quail 4tet | 102 | Pamela Frank | COACHING`
- Changed fields: title
- Before:
  - `2026-06-27 13:15:00-14:15:00 | Lesley Coaching: Quail 4tet | 102 | Katie Behroozi, Benjamin Chen, Ben Parks, Cyrus Behroozi | COACHING`
- After:
  - `2026-06-27 13:15:00-14:15:00 | Pam Coaching: Quail 4tet | 102 | Katie Behroozi, Benjamin Chen, Ben Parks, Cyrus Behroozi | COACHING`
- Changed fields: participants
- Before:
  - `2026-06-27 13:15:00-14:15:00 | Quail 4tet | 102 | Lesley Robertson | COACHING`
- After:
  - `2026-06-27 13:15:00-14:15:00 | Quail 4tet | 102 | Pamela Frank | COACHING`
- Changed fields: title, location
- Before:
  - `2026-06-22 15:15:00-16:15:00 | Pedja Coaching: Quartet 94 | 106 | Christine Choi, Bruce Yu, Jessica Seeliger, Warren Wu | COACHING`
- After:
  - `2026-06-22 15:15:00-16:15:00 | Pam Coaching @ Dolores: Quartet 94 | 776 Dolores St, Stanford, CA | Christine Choi, Bruce Yu, Jessica Seeliger, Warren Wu | COACHING`
- Changed fields: title, location, participants
- Before:
  - `2026-06-22 15:15:00-16:15:00 | Quartet 94 | 106 | Pedja Muzijevic | COACHING`
- After:
  - `2026-06-22 15:15:00-16:15:00 | Quartet 94 @ Dolores | 776 Dolores St, Stanford, CA | Pamela Frank | COACHING`
- Changed fields: title, location
- Before:
  - `2026-06-24 15:15:00-16:15:00 | Pedja Coaching: Quartet 94 | 106 | Christine Choi, Bruce Yu, Jessica Seeliger, Warren Wu | COACHING`
- After:
  - `2026-06-24 15:15:00-16:15:00 | Pam Coaching @ Dolores: Quartet 94 | 776 Dolores St, Stanford, CA | Christine Choi, Bruce Yu, Jessica Seeliger, Warren Wu | COACHING`
- Changed fields: title, location, participants
- Before:
  - `2026-06-24 15:15:00-16:15:00 | Quartet 94 | 106 | Pedja Muzijevic | COACHING`
- After:
  - `2026-06-24 15:15:00-16:15:00 | Quartet 94 @ Dolores | 776 Dolores St, Stanford, CA | Pamela Frank | COACHING`
- Changed fields: title, location
- Before:
  - `2026-06-26 15:15:00-16:15:00 | Pedja Coaching: Quartet 94 | 106 | Christine Choi, Bruce Yu, Jessica Seeliger, Warren Wu | COACHING`
- After:
  - `2026-06-26 15:15:00-16:15:00 | Pam Coaching @ Dolores: Quartet 94 | 776 Dolores St, Stanford, CA | Christine Choi, Bruce Yu, Jessica Seeliger, Warren Wu | COACHING`
- Changed fields: title, location, participants
- Before:
  - `2026-06-26 15:15:00-16:15:00 | Quartet 94 | 106 | Pedja Muzijevic | COACHING`
- After:
  - `2026-06-26 15:15:00-16:15:00 | Quartet 94 @ Dolores | 776 Dolores St, Stanford, CA | Pamela Frank | COACHING`
- Changed fields: title, location
- Before:
  - `2026-06-22 14:00:00-15:00:00 | Dimitri Coaching: The Dolphins | 227 | Luke Henderson, Isaac Park, James Preucil, Ian Maloney | COACHING`
- After:
  - `2026-06-22 14:00:00-15:00:00 | Pam Coaching @ Dolores: The Dolphins | 776 Dolores St, Stanford, CA | Luke Henderson, Isaac Park, James Preucil, Ian Maloney | COACHING`
- Changed fields: title, location, participants
- Before:
  - `2026-06-22 14:00:00-15:00:00 | The Dolphins | 227 | Dimitri Murrath | COACHING`
- After:
  - `2026-06-22 14:00:00-15:00:00 | The Dolphins @ Dolores | 776 Dolores St, Stanford, CA | Pamela Frank | COACHING`
- Changed fields: title
- Before:
  - `2026-06-24 14:00:00-15:00:00 | Dimitri Coaching: The Dolphins | 227 | Luke Henderson, Isaac Park, James Preucil, Ian Maloney | COACHING`
- After:
  - `2026-06-24 14:00:00-15:00:00 | Pam Coaching: The Dolphins | 227 | Luke Henderson, Isaac Park, James Preucil, Ian Maloney | COACHING`
- Changed fields: participants
- Before:
  - `2026-06-24 14:00:00-15:00:00 | The Dolphins | 227 | Dimitri Murrath | COACHING`
- After:
  - `2026-06-24 14:00:00-15:00:00 | The Dolphins | 227 | Pamela Frank | COACHING`
- Changed fields: title
- Before:
  - `2026-06-26 14:00:00-15:00:00 | Dimitri Coaching: The Dolphins | 227 | Luke Henderson, Isaac Park, James Preucil, Ian Maloney | COACHING`
- After:
  - `2026-06-26 14:00:00-15:00:00 | Pam Coaching: The Dolphins | 227 | Luke Henderson, Isaac Park, James Preucil, Ian Maloney | COACHING`
- Changed fields: participants
- Before:
  - `2026-06-26 14:00:00-15:00:00 | The Dolphins | 227 | Dimitri Murrath | COACHING`
- After:
  - `2026-06-26 14:00:00-15:00:00 | The Dolphins | 227 | Pamela Frank | COACHING`

## Affected People

Anthony Manzo, Ben Parks, Benjamin Chen, Bruce Yu, Cary Chin, Christine Choi, Cyrus Behroozi, Dimitri Murrath, Gregorio Lopes, Ian Maloney, Isaac Park, James Preucil, James Welch, Jessica Seeliger, Jim Zehnder, Katie Behroozi, Ko Hayashi, Lesley Robertson, Luke Henderson, Mark Siegel, Pamela Frank, Pedja Muzijevic, Persis Drell, Ron Ho, Warren Wu

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
