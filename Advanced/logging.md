# Logging in python
Logging is a means of tracking events that happen when some software runs. The software’s developer adds logging calls to their code to indicate that certain events have occurred. An event is described by a descriptive message which can optionally contain variable data (i.e. data that is potentially different for each occurrence of the event). Events also have an importance which the developer ascribes to the event; the importance can also be called the level or severity.
- You can access logging functionality by creating a logger via logger = getLogger(__name__).
## Levels
| Level | When it’s used |
|----------|----------|
| DEBUG    | Detailed information, typically of interest only when diagnosing problems.   |
| INFO    | Confirmation that things are working as expected.   |
| WARNING    | An indication that something unexpected happened, or indicative of some problem in the near future (e.g. ‘disk space low’). The software is still working as expected.   |
| ERROR    | Due to a more serious problem, the software has not been able to perform some function.   |
| CRITICAL    | A serious error, indicating that the program itself may be unable to continue running.   |
