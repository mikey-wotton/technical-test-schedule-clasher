# Technical Test

## The Task
The task is to build a schedule-clash detecting tool. The tool will consume two User's weeks of schedules and 
return all the periods in which the schedules clash. Schedules clash if two periods of time overlap for at least 15
 minutes.
 
 We expect to see at a minimum:
 1. Tests on any non-simple or critical functionality.
 2. Code coverage of above Unit tests to be at least 50%.
 3. An ASSUMPTIONS.md file detailing any assumptions you made and your reasoning.
 
## Data
 * The schedules are in the ./data folder in the format JSON, each file is a separate set of schedules.
 * A file is a single JSON object, inside of which has 2 separate schedules. One schedule has key "user1", the other is "user2".
 * Period formatting is provided in RFC3339 standard time format.
