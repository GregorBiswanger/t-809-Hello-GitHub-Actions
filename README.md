# t-809-Hello-GitHub-Actions

[![Hello World](https://github.com/GregorBiswanger/t-809-Hello-GitHub-Actions/actions/workflows/hello-workflow.yml/badge.svg)](https://github.com/GregorBiswanger/t-809-Hello-GitHub-Actions/actions/workflows/hello-workflow.yml)

GitHub Actions Workshop Beispiel...

0 → Minute
Wertebereich: 0-59
Hier also: in Minute 0.

6 → Stunde
Wertebereich: 0-23
Hier also: um 06:00 Uhr.

* → Tag des Monats
Wertebereich: 1-31
Das Sternchen bedeutet: egal welcher Tag im Monat.

* → Monat
Wertebereich: 1-12 oder JAN-DEC
Also: jeder Monat.

* → Wochentag
Wertebereich: 0-6 oder SUN-SAT
Also: jeder Wochentag.

Unterm Strich heißt 0 6 * * * also:
Jeden Tag um 06:00 UTC.

# Jeden Tag um Mitternacht
- cron: '0 0 * * *'

# Jeden Tag um 06:30
- cron: '30 6 * * *'

# Jeden Montag um 08:00
- cron: '0 8 * * 1'

# Montag bis Freitag um 07:15
- cron: '15 7 * * 1-5'

# Jede volle Stunde
- cron: '0 * * * *'

# Alle 15 Minuten
- cron: '*/15 * * * *'