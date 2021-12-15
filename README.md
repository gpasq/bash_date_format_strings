# Bash Date Format Strings

Date formatting is not hard, but it's always a pain in the ass that I have to RTFM then do several tests to make sure I'm getting it right. Here's a simple table of common formatting strings to match what you need.

| Format   |      Command       |   |
|----------|:-------------:|------:|
| 12/15/2021 |  date +%x | Locale date |
| 10:20:35 |  date +%X | Locale time |
| 2021-12-15T10:27:18 | date +"%Y-%m-%dT%H:%M:%S" | ISO-8601-ish |
| 2021-12-15T10:25:39-0600 | date +"%Y-%m-%dT%H:%M:%S%z" | ISO-8601 |
