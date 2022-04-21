# Technical Test

## The Task
The task is to build a schedule-clash detecting tool. The tool will consume two User's weeks of schedules and 
return all the periods in which the schedules clash. Schedules clash if two periods of time overlap for at least 15
 minutes.
 
 We expect to see at a minimum:
 1. A sensible Golang folder structure, making using of go.mod.
 2. Unit tests on at least exported functions of packages, maybe more if needed.
 3. Code coverage of above Unit tests to be at least 50%.
 4. An ASSUMPTIONS.md file detailing any assumptions you made and your reasoning.
 
## Data
 * The schedules are in the ./data folder in the format JSON, each file is a separate set of schedules. 
 * Period formatting is provided in RFC3339 standard time format.
